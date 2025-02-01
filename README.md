# Travel-Planner-Multi-AI-Agent

# Travel Planner

## Overview
The **Travel Planner** is an intelligent itinerary generator leveraging natural language processing and graph-based state management. This project integrates with a language model to create personalized travel plans based on user preferences such as city and interests.

## Features
- **StateGraph Integration:** Manages the flow of the travel planning process.
- **Custom PlannerState:** Defines the structure of the planning data.
- **Dynamic Node Functions:** Handles specific user inputs like city selection and interests.
- **LLM Integration:** Utilizes a language model to generate tailored itineraries.

## Technologies Used
- **Python**
- **LangChain & LangGraph:** For managing conversational flows.
- **TypedDict & Annotated:** For structured data management.
- **Jupyter Notebook:** For development and demonstration.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/travel-planner.git
   ```
2. Navigate to the project directory:
   ```bash
   cd travel-planner
   ```
3. Install the required packages:
   ```bash
   pip install langchain langchain_core langchain_groq langchain_community langgraph
   ```

## Usage
1. Open the notebook:
   ```bash
   jupyter notebook Travel_Planner.ipynb
   ```
2. Run the cells sequentially to:
   - Define the agent and its functions.
   - Input your travel preferences.
   - Generate a customized itinerary.

## Project Structure
- `StateGraph:` Defines the core logic and flow.
- `PlannerState:` Maintains the state of the travel planning process.
- `Node Functions:` Manages inputs like city, interests, and generates itineraries.
- `LLM Integration:` Interfaces with a language model for itinerary generation.

## Example
- **Input:**
  - City: *Paris*
  - Interests: *Museums, Cafes, Historic Sites*
- **Output:**
  - A detailed 1-day itinerary with activities tailored to the provided interests.

## Contributing
Contributions are welcome! Feel free to fork the repository, make changes, and submit a pull request.

## Acknowledgments
- Special thanks to the LangChain community for their comprehensive documentation and support.

