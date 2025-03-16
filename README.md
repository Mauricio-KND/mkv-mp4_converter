# MKV to MP4 Conversion Python Program

This simple Python program converts MKV video files to MP4 format. It provides a user-friendly interface for selecting an MKV file and performing the conversion. The program uses the `ffmpeg-python` library for the conversion process.

## Features

- Converts MKV files to MP4 format.
- User-friendly interface using the `tkinter` library.
- Supports basic video and audio codec options.

## Getting Started

### Prerequisites

- Python (3.6 or higher) installed on your system.
- FFmpeg installed (used by `ffmpeg-python` for conversion).

### Installation

1. Clone or download this repository to your local machine.

   ```bash
   git clone https://github.com/Mauricio-KND/mkv-mp4_converter.git
   cd mkv-mp4_converter

   ```

2. Set up a virtual environment named 'venv' (optional but recommended):

   ```bash
   python3 -m venv venv

   ```

3. Activate the virtual environment:

   ```bash
   # Windows
   venv\Scripts\activate

   # macOS or Linux
   source venv/bin/activate

   ```

4. Install the required libraries:

   ```bash
   pip install ffmpeg-python
   ```

## Usage

1. Run the script:

   ```bash
   python mkv_to_mp4_converter.py
   ```

- The program will prompt you to select an MKV file for conversion using a file dialog.
- After selecting the file, the program will perform the conversion to MP4 format.
- The converted MP4 file will be saved in the same directory as the input MKV file.

## Contributing

Contributions are welcome! If you have suggestions, improvements, or bug fixes, feel free to open an issue or a pull request in the GitHub repository.

## License

This project is licensed under the MIT License.
