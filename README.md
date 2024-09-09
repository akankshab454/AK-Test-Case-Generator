
# AK Test Case Generator 

## Overview
The **AK Test Case Generator** simplifies the QA process by automatically generating detailed test cases for digital product features based on uploaded screenshots and optional context. Powered by a multimodal Large Language Model (LLM), this tool helps testers save time and ensures comprehensive testing.

## Features
- **Upload Multiple Screenshots**: Users can upload screenshots of the digital product.
- **Optional Context Input**: Additional context can be provided to refine the test case generation.
- **AI-Generated Test Cases**: Automatically generate test cases including descriptions, pre-conditions, step-by-step testing instructions, and expected outcomes.

## How It Works
1. **Upload Screenshots**: Add multiple screenshots using the file uploader.
2. **Optional Context**: Add any additional details to guide test case creation.
3. **Generate Test Cases**: Click "Generate" to send the images and context to an LLM-powered API.
4. **View Results**: The tool outputs test cases, including feature descriptions, steps, and expected results.

### Example Test Case Outputs
1. **Search for Bus Tickets**: Test the search feature for accurate results.
2. **View Bus Details**: Ensure that bus details (timing, pricing) are correctly displayed.
3. **Book Bus Tickets**: Validate the booking process, from selecting seats to payment.
4. **View Booking History**: Confirm that past bookings and relevant details are accurately shown.

## Tech Stack
- **Front-end**: Streamlit for an intuitive, interactive UI.
- **Back-end**: AWS Lambda handles image processing and API integration.
- **LLM**: A multimodal Large Language Model processes screenshots to generate test cases.

## Installation & Setup
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/test-case-generator
   cd test-case-generator
   ```
2. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Streamlit app:
   ```bash
   streamlit run app.py
   ```

## Usage
1. **Upload Screenshots**: Start by uploading screenshots of the digital product.
2. **Enter Context**: Optionally, provide context in the text box.
3. **Generate Test Cases**: Click the “Generate” button to create detailed test cases.
4. **Review Results**: View the generated test cases directly within the app.

## Results
![Result1](https://github.com/user-attachments/assets/f9cf271b-fa67-4fa5-a09e-4cf3559271c0)
![Result3](https://github.com/user-attachments/assets/1b7438fe-7fe3-4a0d-9049-b1793dd1d85a)
![Result2](https://github.com/user-attachments/assets/110c5be2-a61b-49fd-b12d-1aaaa991d0b0)
