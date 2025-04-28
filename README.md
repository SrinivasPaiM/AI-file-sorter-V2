# AI File Organizer

An intelligent file organization system that uses machine learning to automatically categorize and sort files based on their names, extensions, and content patterns.

## Features

- 🤖 AI-powered file categorization using multiple methods:
  - Extension-based matching
  - Keyword-based matching
  - Machine learning prediction
- 📁 Comprehensive file type support:
  - Documents (PDF, DOCX, TXT, etc.)
  - Media files (Images, Videos, Audio)
  - Code files (Python, JavaScript, etc.)
  - Design files (PSD, AI, FIGMA)
  - Modern formats (GDOC, NOTION, AIRTABLE)
- 🔍 Advanced pattern recognition:
  - Date patterns
  - Version numbers
  - Status indicators
- 💾 Automatic backup creation
- 📊 Progress tracking and reporting

## Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/ai-file-organizer.git
cd ai-file-organizer
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

## Usage

```python
from advanced_sort import ai_based_sort

# Basic usage
ai_based_sort("path/to/your/directory")

# With progress callback
def progress_callback(message):
    print(message)

ai_based_sort("path/to/your/directory", progress_callback=progress_callback)
```

## Configuration

The system uses three main configuration files:

1. `file_categories.py`: Contains file patterns, keywords, and training examples
2. `advanced_sort.py`: Main sorting logic and AI implementation
3. `requirements.txt`: Project dependencies

## Supported File Categories

- Documents
- Spreadsheets
- Presentations
- Images
- Videos
- Audio
- Code
- Data
- Config
- Archives
- Executables
- Design
- Fonts
- 3D Models
- Web
- Cloud
- Project Management
- Security
- Mobile Development
- Machine Learning
- Container
- Game Development
- CAD

## Example

```python
# Example directory structure before sorting
your_directory/
├── report_2024.pdf
├── project.py
├── design.fig
├── meeting.mp4
└── data.json

# After running the organizer
your_directory/
├── documents/
│   └── report_2024.pdf
├── code/
│   └── project.py
├── design/
│   └── design.fig
├── videos/
│   └── meeting.mp4
└── data/
    └── data.json
```

## Screenshots

[Optional: Add screenshots of the organized files and progress output]

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Built with Python and scikit-learn
- Uses advanced pattern matching and machine learning techniques
- Inspired by modern file organization needs 