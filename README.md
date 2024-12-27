# Local LLM for Cancer Registry - Chatbot for Moffitt Researchers, Clinicians, and Registrars

This GitHub repository contains the **winning first-place solution** for the proof-of-concept model in the competition.

## Overview

The **Moffitt Path Report Viewer** is a Python-based application designed to visualize and interact with pathology reports from the Moffitt system. Leveraging powerful libraries, this tool provides an intuitive interface for accessing, viewing, and managing pathology data efficiently.

## Features

- **MongoDB Integration:** Connects to MongoDB to retrieve and manage pathology reports.
- **Interactive Interface:** Built with Streamlit for a user-friendly and interactive experience.
- **Data Processing:** Utilizes Pandas for efficient data manipulation and analysis.
- **Unique Identification:** Generates unique identifiers for reports using UUID.
- **Real-Time Updates:** Handles real-time data processing and updates seamlessly.

## Installation

### Prerequisites

- **Python:** Ensure you have Python 3.7 or higher installed. You can download it from [python.org](https://www.python.org/downloads/).

### Clone the Repository

```bash
git clone https://github.com/yourusername/moffitt-path-report-viewer.git
cd moffitt-path-report-viewer
```

### Install Required Packages

Install the necessary Python packages using `pip`:

```bash
pip install pymongo groq streamlit pandas
```

**Note:** The following packages are part of Python's standard library and do not require separate installation:

- `os`
- `json`
- `bson` (included with `pymongo`)
- `io`
- `uuid`
- `time`

## Usage

1. **Configure MongoDB Connection:**

   Ensure your MongoDB instance is running and update the connection details in your Python script if necessary.

2. **Run the Application:**

   Execute the Streamlit application using the following command:

   ```bash
   streamlit run main.py
   ```

3. **Access the Viewer:**

   Once the application is running, open your web browser and navigate to the URL provided in the terminal (usually `http://localhost:8501`).

## Dependencies

The project relies on the following Python libraries:

- **os:** Interacting with the operating system. [Documentation](https://docs.python.org/3/library/os.html)
- **json:** Handling JSON data. [Documentation](https://docs.python.org/3/library/json.html)
- **pymongo:** MongoDB driver for Python. [Documentation](https://pymongo.readthedocs.io/)
- **bson.objectid:** Handling BSON ObjectIds, included with `pymongo`. [Documentation](https://pymongo.readthedocs.io/en/stable/api/bson/objectid.html)
- **groq:** Querying with GROQ language. [Documentation](https://groq.readthedocs.io/)
- **streamlit:** Building interactive web applications. [Documentation](https://docs.streamlit.io/)
- **pandas:** Data manipulation and analysis. [Documentation](https://pandas.pydata.org/)
- **io:** Handling I/O operations. [Documentation](https://docs.python.org/3/library/io.html)
- **uuid:** Generating unique identifiers. [Documentation](https://docs.python.org/3/library/uuid.html)
- **time:** Time-related functions. [Documentation](https://docs.python.org/3/library/time.html)

## Contributing

Contributions are welcome! If you have suggestions, improvements, or bug fixes, please open an issue or submit a pull request.

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/YourFeature`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature/YourFeature`).
5. Open a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

