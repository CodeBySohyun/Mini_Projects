### face_swap.ipynb

This notebook implements a face-swapping algorithm on video data. It employs the `insightface` library for face detection and uses computer vision techniques to replace faces in video frames. Multithreaded processing allows for efficient handling of video data. The final output is a video with the face swapped, matched with the original audio.

- **Key Libraries**: `cv2`, `insightface`, `imageio`, `matplotlib`
- **Functionality**:
  - Face detection and swapping using deep learning models.
  - Parallel frame processing for enhanced performance.
  - Audio extraction and synchronisation with swapped video.
  - Final video generation with original audio.

The notebook is structured to be a standalone application for face swapping in videos, complete with audio management and visualisation of results.

### voice_transcription.ipynb

This notebook provides an automated process for transcribing audio files using speech recognition. It is tailored to handle `.m4a` files, converting them into `.wav` format, and then utilising the Google Speech Recognition API to transcribe the audio into text.

- **Key Libraries**: `pydub`, `speech_recognition`, `tqdm`
- **Functionality**:
  - Converts `.m4a` audio files to `.wav` format for compatibility with speech recognition services.
  - Chunks long audio files into manageable segments for reliable transcription.
  - Transcribes audio using Google's Speech Recognition API and writes results to a text file.
  - Manages files and directories to organise audio and transcription data.
  - Displays progress during transcription with an interactive progress bar.

This notebook is especially useful for projects requiring the conversion of spoken content into written form, such as generating transcripts for lectures or interviews.

### jupyter_code_saver.ipynb

This notebook provides a utility for extracting all code cells from a Jupyter notebook and saving them as a standalone Python script. It's a handy tool for sharing code or preparing it for production environments where Jupyter notebooks are not the preferred format.

- **Key Libraries**: `os`, `nbformat`
- **Functionality**:
  - Reads a Jupyter notebook and extracts code cells.
  - Creates a Python script with the extracted code, maintaining the original structure and comments.
  - Saves the script in the same directory for easy access and version control.

This notebook facilitates the seamless transition from interactive data analysis to script-based execution.
