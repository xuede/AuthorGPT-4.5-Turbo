AuthorGPT-4.5-Turbo
This is based on mshumer's author-gpt.
I updated the completion API called. Included a static element at the end of the prompt to dissuade the AI from using it's overused words. I made some cosmetic changes and added Google Drive support.
I've generated magical realism, literary fiction, and children's stories.

From the original project:
'''This project utilizes a chain of GPT-4, Stable Diffusion, and Anthropic API calls to generate an original novel. Users can provide an initial prompt and enter how many chapters they'd like it to be, and the AI then generates an entire novel, outputting an EPUB file compatible with e-book readers.'''


## How It Works

The AI is asked to generate a list of potential plots based on a given prompt. It then selects the most engaging plot, improves upon it, and extracts a title. After that, it generates a detailed storyline with a specified number of chapters, and then tries to improve upon that storyline. Each chapter is then individually written by the AI, following the plot and taking into account the content of previous chapters. Finally, a prompt to design the cover art is generated, and the cover is created. Finally, it's all pulled together, and the novel is compiled into an EPUB file.

## Usage

Open the Colab notebook. Set you Colab secrets. Fill in the chapter numbers, plot and writing style.
Run the cells!

## License

This project is [MIT](https://github.com/your_username/your_repository/blob/master/LICENSE) licensed.

## Thanks to Matt Schumer who's original work this is built on.

Matt Shumer - [@mattshumer_](https://twitter.com/mattshumer_)
Project Link: [https://github.com/mshumer/gpt-author/](https://github.com/mshumer/gpt-author/ )
