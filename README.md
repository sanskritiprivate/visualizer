# Pharmaceutical Research Data Visualization Platform

## Overview
Built a visualization platform for pharmaceutical companies to explore and analyze their research data.

## Tech Stack
- **Languages**: Python, R
- **Framework**: Dash
- **Cloud Services**: AWS
- **Containerization**: Kubernetes
- **Data Format**: JSON

## Project Details
This project consists of two main components:

1. **Parser**: 
   - The parser processes large datasets from pharmaceutical experiments. It accepts specific file types as input and converts them into JSON format. 
   - To run the parser, execute the main function in the parser module and provide the input and output file paths, along with an optional indentation level.
   - Example usage:
     ```bash
     python parser.py --input <input_file_path> --output <output_file_path> [--indent <indentation_level>]
     ```

2. **Viewer**: 
   - The viewer is built using Dash and allows users to visualize the parsed data through interactive dashboards.
   - To run the viewer, execute the `app_handler.py` file, which initializes the Dash application.
   - When the application is running, you can add a link to the parsed file stored in an S3 bucket to view that particular file.
   - Example usage:
     ```bash
     python app_handler.py
     ```

## Features
- Interactive dashboards to explore trends and insights in real-time.
- Custom parsers for various file formats to ensure compatibility with pharmaceutical datasets.
- High availability and scalability achieved through deployment on AWS.

## Getting Started
1. **Clone the Repository**:
   ```bash
   git clone <repository_url>
   cd pharmaceutical-research-visualization
