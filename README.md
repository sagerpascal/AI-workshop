# AI Workshop

An AI workshop for undergraduate students to get them excited about AI - taught at the Zurich University of Applied Sciences (ZHAW).

## Structure
- **Docs**: Contains the source code for the presentation slides/website, built with Jekyll and WebSlides.
  - Part I: Introduction to AI, examples, and risks.
  - Part II: Practical workshop using Teachable Machine and Python (Learnbot).
- **Notebooks**: Contains Jupyter notebooks used in the workshop (e.g., `p2_learnbot.ipynb`).

The presentations are created using [WebSlides](https://webslides.tv).

## Website
For more information, please visit the [AI Workshop website](https://sagerpascal.github.io/AI-workshop/).

## Build Website Locally

1. Navigate to the `docs` directory:
   ```bash
   cd docs
   ```
2. Install dependencies:
   ```bash
   bundle install
   ```
3. Run the Jekyll server:
   ```bash
   bundle exec jekyll serve
   ```
   Note: You might need to add webrick if using Ruby 3.0+:
   ```bash
   bundle add webrick
   ```
