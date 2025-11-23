# Image Quiz Website

A simple, elegant quiz website featuring 15 pages with image-based questions.

## Features

- **Index Page**: Main landing page with a grid display of all 15 quiz questions
- **15 Quiz Pages**: Each page displays an image as a quiz question with multiple-choice options
- **Easy Navigation**: Navigate between questions with previous/next buttons and return to home
- **Responsive Design**: Mobile-friendly layout that works on all devices
- **Modern UI**: Clean, gradient-based design with smooth animations

## Structure

```
quiz/
├── index.html          # Main landing page with quiz navigation
├── quiz1.html          # Quiz question 1
├── quiz2.html          # Quiz question 2
├── ...                 # Quiz questions 3-14
├── quiz15.html         # Quiz question 15
├── style.css           # Stylesheet for all pages
└── README.md           # This file
```

## Usage

1. Open `index.html` in a web browser to start
2. Click on any quiz card (1-15) to view that question
3. Each quiz page displays:
   - A placeholder for the quiz image
   - The question text
   - Four multiple-choice options (A, B, C, D)
   - Navigation buttons to move between questions

## Customization

### Adding Quiz Images

To add your quiz images, replace the placeholder text in each quiz page:

```html
<div class="quiz-image">
    [Image Placeholder - Add your quiz image here]
</div>
```

Replace with:

```html
<img src="path/to/your/image.jpg" alt="Quiz question" class="quiz-image">
```

### Updating Questions and Options

Edit the question text and options in each `quizX.html` file:

```html
<div class="quiz-question">
    <p>Your question here?</p>
</div>

<div class="quiz-options">
    <div class="option">A. Your option 1</div>
    <div class="option">B. Your option 2</div>
    <div class="option">C. Your option 3</div>
    <div class="option">D. Your option 4</div>
</div>
```

## Deployment

This is a static website that can be deployed to:
- GitHub Pages
- Netlify
- Vercel
- Any static web hosting service

Simply upload all files to your hosting service and navigate to `index.html`.

## Browser Support

Works on all modern browsers:
- Chrome
- Firefox
- Safari
- Edge

## License

Feel free to use and modify this quiz website for your needs.