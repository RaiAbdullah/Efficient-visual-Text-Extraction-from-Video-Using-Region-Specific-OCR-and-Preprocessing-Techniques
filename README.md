# MERN Stack Web Application for Text Extraction from Video Using Region-Specific OCR and Preprocessing Techniques

## Overview
This project is a full-stack MERN (MongoDB, Express.js, React.js, Node.js) web application designed to extract text from video files using region-specific Optical Character Recognition (OCR) and various preprocessing techniques. The application supports user-uploaded videos with options for region selection to improve OCR accuracy.

## Project Structure
The project is divided into two main parts:
- **Frontend**: Implements the user interface using React.js.
- **Backend**: Handles video processing, frame extraction, image preprocessing, and OCR operations using Node.js and Express.js.

## Features

### Frontend
- **User Interface**: Built with React.js for an interactive, responsive design.
- **Video Upload**: Users can upload video files directly through the interface.
- **Region Selection**: Users can specify a region of interest (x, y, width, height) before uploading to optimize text extraction.
- **Display Results**: Extracted text is sent from the backend and displayed on the frontend.

### Backend
- **Video Processing**: Video files are processed using Node.js libraries to extract frames.
- **Region-Based Cropping**: Frames are cropped based on user-specified coordinates to focus on regions containing text.
- **Preprocessing Techniques**:
  - **Grayscale Conversion**: Converts colored frames to grayscale for better OCR performance.
  - **Noise Removal**: Reduces noise to improve text clarity.
  - **Binarization**: Converts frames to a black-and-white format to enhance text visibility.
  - **Skew Correction**: Aligns tilted text for accurate recognition.
- **OCR Integration**: Uses Tesseract.js to perform OCR on the processed frames and extract text.
- **Error Handling**: Includes error handling for invalid input or processing issues.
- **Batch Processing**: Processes frames in batches to improve performance and manage resource usage.

## System Workflow
1. **Video Upload**: The user uploads a video file through the frontend.
2. **Region Selection (Optional)**: The user can select a specific region in the video to extract text from that area.
3. **Frame Extraction**: The backend extracts frames from the video at regular intervals.
4. **Frame Cropping**: If a region is specified, frames are cropped accordingly.
5. **Preprocessing**: Frames undergo various preprocessing steps, such as grayscale conversion, noise removal, binarization, and skew correction.
6. **OCR Processing**: Preprocessed frames are processed by Tesseract.js to extract text.
7. **Results Display**: Extracted text is sent back to the frontend and displayed to the user.

## Technologies Used

### Frontend
- React.js
- Axios for API calls
- CSS for styling

### Backend
- Node.js and Express.js for server setup
- FFmpeg for video frame extraction
- Image processing libraries (e.g., Jimp, Sharp)
- Tesseract.js for OCR

### Database
- MongoDB for storing processed video data and user interactions

## Installation and Setup

### Prerequisites
- Node.js
- MongoDB
- FFmpeg installed on the system




#Contact

For access to the complete codebase, reach out via [Email: nawazabdullah18@gmail.com , Whatsapp: 03190988126].
