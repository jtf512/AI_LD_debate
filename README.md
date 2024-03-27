# AI Agents Lincoln-Douglas Debate

This python notebook walks through an example of a cognitive process for researching a topic, constructing arguments around a resolution, cross examining the opposing side, and developing persuasive rebuttals.

The format is a traditional Lincoln-Douglas debate, which is practiced in debate clubs in nearly every major high school in the United States.

The intent of this project was to gain some familiarity with non-OpenAI technologies while testing the capacity for AI "agents" to reason through constructive arguments and rebuttals. 

Likely some form of self-play and philosophical argumentative reasoning along these lines is essential to future generations of artificial intelligence. For now, it is just a stepping stone to various enterprise LLM reasoning applications. 

If this has been useful or interesting to you, please feel free to drop me a line at ferrell [dot] jason [at] gmail [dot] com

## Installation

Ensure you have python installed on your system. This project was developed on version 3.11.

Verify your python version:
python --version

Create a virtual environment:
python -m venv env

Activate the environment:
source env/bin/activate
(on Windows, .\env\Scripts\activate )

Install the dependences:
pip install -r requirements.txt

Create a .env file:
touch .env

In your .env file, include your API keys for the following resources:
REV_API="your_api_key"
ANTHROPIC_KEY="your_api_key"
COHERE_KEY="your_api_key"

## Usage

To start exploring the debate, open Jupyter Notebook or JupyterLab:

jupyter notebook

Navigate to the project directory and open the notebook file.

## License

This project is licensed under the MIT license - see the [LICENSE](LICENSE) file for details