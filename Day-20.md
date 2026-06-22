<img width="1607" height="761" alt="Screenshot 2026-06-22 234710" src="https://github.com/user-attachments/assets/9a41f381-63bf-4a71-bb7f-f62b38b0dd79" />
<img width="1438" height="896" alt="Screenshot 2026-06-22 234653" src="https://github.com/user-attachments/assets/1b32f744-7a40-49a8-8e8a-4bea4b1729a9" />
<img width="1465" height="933" alt="Screenshot 2026-06-22 234640" src="https://github.com/user-attachments/assets/845abf27-1f03-4142-a0f3-fae231db6450" />


# 🎭 FaceOff – AI-Powered Face Puzzle Game

Turn your selfie into an interactive puzzle challenge!

FaceOff is a browser-based puzzle game that captures your face using your device's webcam, slices the image into puzzle pieces, shuffles them into a solvable arrangement, and challenges you to reconstruct your own portrait as quickly as possible.

## ✨ Features

### 📸 Webcam Integration

* Real-time camera preview using `getUserMedia()`
* Front-facing camera support
* One-click photo capture
* Graceful fallback when camera permission is denied
* Upload image option for unsupported environments

### 🧩 Dynamic Puzzle Generation

* Generate puzzles directly from captured photos
* Multiple difficulty levels:

  * 3×3 Grid
  * 4×4 Grid
  * 5×5 Grid
* Automatic image slicing into puzzle pieces
* Randomized yet solvable puzzle layouts

### 🎮 Interactive Gameplay

* Drag-and-drop puzzle pieces
* Mobile touch gesture support
* Piece swapping mechanics
* Visual feedback while dragging
* Correctly placed pieces highlighted automatically

### ⏱️ Performance Tracking

* Live timer (mm:ss.t format)
* Move counter
* Correct piece tracker
* Real-time progress monitoring

### 🏆 Leaderboard System

* Automatic win detection
* Final results summary
* Top 5 best scores saved using Local Storage
* Records include:

  * Completion time
  * Move count
  * Difficulty level
  * Completion date

### 🎨 Modern Responsive UI

* Dark cinematic theme
* Mobile-first responsive design
* Smooth animations
* Results modal
* Retake photo functionality
* Play Again option
* New Photo workflow



## 🛠️ Technologies Used

* HTML5
* CSS3
* Vanilla JavaScript
* Canvas API
* MediaDevices API (`getUserMedia`)
* Local Storage API



## 📱 Browser Compatibility

✅ Google Chrome

✅ Mozilla Firefox

✅ Safari

✅ Edge

> Camera access requires HTTPS or localhost.



## 🚀 How It Works

1. Allow camera access.
2. Capture a selfie.
3. Choose puzzle difficulty.
4. Puzzle pieces are generated and shuffled.
5. Drag pieces into their correct positions.
6. Complete the image before the timer runs out.
7. Compare your score on the leaderboard.



## 🎯 Key Learning Outcomes

This project demonstrates:

* Camera API integration
* Canvas image processing
* Dynamic puzzle generation algorithms
* Touch and drag event handling
* State management in JavaScript
* Local Storage persistence
* Responsive UI/UX design
* Game logic implementation


## 📸 Preview

### Camera Capture Screen

* Live webcam preview
* Snapshot functionality
* Permission handling

### Puzzle Board

* Dynamic image slicing
* Real-time timer and move tracking
* Interactive drag-and-drop gameplay

### Results Dashboard

* Completion statistics
* Difficulty tracking
* Persistent leaderboard



## 🔥 Future Enhancements

* Multiplayer mode
* Online leaderboard
* Custom image uploads
* AI-generated puzzle effects
* Achievement system
* Sound effects and animations
* Puzzle hints system





⭐ If you enjoyed this project, consider starring the repository and sharing your best completion time!
