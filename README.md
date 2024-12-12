# Mac Text Reader

A Streamlit-based text reader application that uses macOS Accessibility API to accurately capture text from your screen.

## Features

- Get active window information
- Capture focused text
- Text history management
- Copy to clipboard functionality
- Real-time text updates

## Installation

```bash
# Clone the repository
git clone https://github.com/keiichimochi/mac-text-reader.git
cd mac-text-reader

# Install required packages
pip install -r requirements.txt
```

## Usage

```bash
# Run the application
streamlit run app.py
```

## Required Permissions

This application needs Accessibility permissions to work:

1. Open System Preferences > Security & Privacy > Privacy > Accessibility
2. Click the lock icon to make changes
3. Add this application to the list and enable it

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

MIT
