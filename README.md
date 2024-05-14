# Finetune_T5-Model_for_Text_Summary


This repository is focused on fine-tuning the T5 model, along with the BART-large-cnn from Facebook, for the task of text summarization on the SAMSum dataset. All code and explanations are contained within a Jupyter Notebook.

## Learning Objectives

By the end of this experiment, you will be able to:
- Fine-tune a T5 model and BART-large-cnn on the SAMSum dataset for summarization.
- Push the fine-tuned model to the Hugging Face model hub.
- Load the fine-tuned model from the hub for inference.

## Dataset Description

The SAMSum dataset includes approximately 16,000 messenger-like conversations with summaries. These conversations were designed by linguists fluent in English to reflect the variety and style of real-life messenger conversations. Summaries provided with the conversations offer concise third-person descriptions of the dialogue content.

### Data Splits
- **Train**: 14,732 samples
- **Validation**: 818 samples
- **Test**: 819 samples

### Data Fields
- `dialogue`: The text of the dialogue.
- `summary`: Human-written summary of the dialogue.
- `id`: Unique ID for each example.

### Example
```json
{
  "id": "13818513",
  "summary": "Amanda baked cookies and will bring Jerry some tomorrow.",
  "dialogue": "Amanda: I baked cookies. Do you want some?\r\nJerry: Sure!\r\nAmanda: I'll bring you tomorrow :-)"
}
```

## How to Use

### Requirements
Ensure you have Python and the following packages installed:
- `transformers`
- `torch`
- `datasets`

You can install these packages using pip:
```bash
pip install transformers torch datasets
```

### Getting Started

1. **Clone the Repository:**
```bash
git clone https://github.com/Praveen76/Finetune_T5-Model_for_Text_Summary.git
cd Finetune_T5-Model_for_Text_Summary
```

2. **Open the Jupyter Notebook:**
   - Launch Jupyter Notebook in the project directory:
   ```bash
   jupyter notebook
   ```
   - Open the `Finetune_T5model_for_Text_Summary.ipynb` file.

3. **Follow the Instructions in the Notebook:**
   - The notebook includes detailed steps for loading the data, training the model, pushing the model to the Hugging Face Hub, and performing inference.

## Contributing

Contributions to improve the project are welcome. Feel free to fork the repository, make changes, and submit a pull request.
---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE.md) file for details.
---
## Contributing

Contributions are welcome! Please feel free to submit a pull request or open an issue if you have suggestions or improvements.
---

## License

This project is licensed under the [MIT License](LICENSE).

# Issues:
If you encounter any issues or have suggestions for improvement, please open an issue in the Issues section of this repository.

---
# Contact:
The code has been tested on Windows system. It should work well on other distributions but has not yet been tested. In case of any issue with installation or otherwise, please contact me on [Linkedin](https://www.linkedin.com/in/praveen-kumar-anwla-49169266/)

Happy coding!!

---
## **About Me**:
I’m a seasoned Data Scientist and founder of [TowardsMachineLearning.Org](https://towardsmachinelearning.org/). I've worked on various Machine Learning, NLP, and cutting-edge deep learning frameworks to solve numerous business problems.
