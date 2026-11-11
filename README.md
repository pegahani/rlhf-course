# Reinforcement learning from human feedback

Course materials for the master's course by Pegah Alizadeh, 2026–2027.
New sessions are added here as the course goes on.

## Sessions

| Session | Topic | Materials |
|---|---|---|
| 1 | from base models to RLHF | [Slides (PDF)](lecture-1/slides.pdf) · [lab-01-sft](https://colab.research.google.com/github/pegahani/rlhf-course/blob/main/lecture-1/lab/lab-01-sft.ipynb) · [hw0-llm-basics](https://colab.research.google.com/github/pegahani/rlhf-course/blob/main/lecture-1/homework/hw0-llm-basics.ipynb) |
| 2 | preferences and reward models | [Slides (PDF)](lecture-2/slides.pdf) · [lab-02-reward-model](https://colab.research.google.com/github/pegahani/rlhf-course/blob/main/lecture-2/lab/lab-02-reward-model.ipynb) · [hw1-bradley-terry](https://colab.research.google.com/github/pegahani/rlhf-course/blob/main/lecture-2/homework/hw1-bradley-terry.ipynb) |
| 3 | reinforcement learning for language models | [Slides (PDF)](lecture-3/slides.pdf) |

## Running the notebooks

Every notebook runs on a free T4 GPU, on **either Colab or Kaggle**.

- **Google Colab:** click a notebook link above. Then *Runtime → Change runtime type → T4 GPU*.
- **Kaggle:** create a new notebook, choose *File → Import notebook*, and paste the notebook's GitHub link. Then turn
  on a T4 under *Settings → Accelerator*. Kaggle asks for a verified phone number before giving you a GPU.

If one platform has no GPU available, use the other: the notebooks are the same.

## Main references

- N. Lambert, *Reinforcement Learning from Human Feedback*: [rlhfbook.com](https://rlhfbook.com)
- S. Truong, A. Haupt, S. Koyejo, *Machine Learning from Human Preferences*: [mlhp.stanford.edu](https://mlhp.stanford.edu)
