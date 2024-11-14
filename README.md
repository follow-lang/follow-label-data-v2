# Generate train data for follow model

This repo will generate data of `Follow-Lang/set.mm.label` in huggingface.

## Format

- The data is located in datasets/train.
- Each line is formatted as: `s label arguments`.
- The maximum word length is 1024.
- All vocabulary words are listed in `words.txt` based on `Follow-Lang/set.mm.proof`.
- The data was generated with a depth of 2.

If you need additional data, feel free to reach out.

This version improves readability and flow while maintaining the original meaning.
