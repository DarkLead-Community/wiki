<img src='docs/images/DarkLead!.png'>

# 

This is the official repository for **DL! - E.C.H.O.**, an enhanced fork of the original [CTF101](https://github.com/osirislab/ctf101) project. Our goal is to expand upon the excellent foundational content by adding new content, supplementary information, updated tutorials, and fostering community contributions.

You can visit our live site (once deployed) at `https://wiki.darklead.org`

This branch primarily uses [MKdocs](https://www.mkdocs.org/) for static site generation and leverages [MKdocs-Material](https://squidfunk.github.io/mkdocs-material/) for a modern, customizable theme.

The original CTF101 was maintained by the [OSIRIS Lab](https://osiris.cyber.nyu.edu/) in collaboration with [CTFd](https://ctfd.io/). We are deeply grateful for their foundational work and commitment to open-source education.

---

## What's New / Our Vision

* **Expanded Content:** We aim to add more in-depth explanations, practical examples, and potentially new categories of CTF challenges.
* **Community Focus:** This fork is driven by community contributions, encouraging new ideas and diverse perspectives.
* **Up-to-Date Resources:** Keeping pace with the evolving cybersecurity landscape, we'll strive to include the latest tools and techniques.

---

### Installation (To run this project locally)

1.  Verify **python 3** and **python-pip** are installed. Otherwise, you can find installation instructions [here](https://www.python.org/downloads/).
    ```sh
    python3 --version
    pip --version
    ```

2.  Clone *this* repository.
    ```sh
    git clone [https://github.com/](https://github.com/)[YOUR GITHUB USERNAME]/[YOUR REPO NAME].git
    cd [YOUR REPO NAME]
    ```

3.  Create a virtual environment (highly recommended). If this step doesn't work, follow this for [**python-venv**](https://packaging.python.org/en/latest/guides/installing-using-pip-and-virtual-environments/).
    ```sh
    python3 -m venv .venv
    source .venv/bin/activate
    ```

4.  Install the necessary packages.
    ```sh
    pip install -r requirements.txt
    ```

5.  Run the development server.
    ```sh
    mkdocs serve
    ```
    You can typically access the local site at `http://127.0.0.1:8000`.

---

### Contributing

> First off, thank you for considering contributing to **[YOUR PROJECT NAME]**! This project thrives on community involvement, and your contributions are invaluable in making this a comprehensive resource for aspiring security engineers.

We welcome all contributions, big or small, from fixing typos to adding entirely new sections.

1.  **Open an Issue:** If you have an idea for a new feature, content update, or find a bug, please start by [opening an issue](https://github.com/[YOUR GITHUB USERNAME]/[YOUR REPO NAME]/issues). This allows for discussion and avoids duplicate work.
2.  **Fork and Branch:**
    * Fork *this* repository to your own GitHub account.
    * Create a new branch from `main` for your changes (e.g., `git checkout -b feature/new-exploit-guide` or `fix/typo-on-web-page`).
3.  **Make Your Changes:** Implement your additions, fixes, or improvements.
4.  **Test Locally:** Ensure your changes work as expected by running `mkdocs serve` locally.
5.  **Commit and Push:** Write clear, concise commit messages.
    ```sh
    git add .
    git commit -m "feat: added new content on X topic"
    git push origin your-branch-name
    ```
6.  **Submit a Pull Request (PR):**
    * Open a Pull Request from your branch back to the `main` branch of *this* repository.
    * Please provide a detailed description of your changes in the PR.
    * Link to any relevant [issues](https://github.com/[YOUR GITHUB USERNAME]/[YOUR REPO NAME]/issues) in your PR description (e.g., `Closes #[issue_number]`).

We appreciate your help in making [YOUR PROJECT NAME] the best resource it can be!

---

### License

This project is open sourced under the MIT Open Source License. For more information, please see the [LICENSE](LICENSE) file in this repository or refer to the [MIT License](https://tlo.mit.edu/understand-ip/exploring-mit-open-source-license-comprehensive-guide) page.

````