## Deep Learning and Software Synthesisers
##### <span style="font-family:Helvetica Neue; font-weight:bold"><span style="color:#e49436">Artificial Assistants</span> That Program Synthesisers</span>

---

## Motivations
<br>
- AI that makes VSTs produce a desired sound |
- Enables the user to focus on music |

---

## Objectives
<br>
- Hacking with VSTs hosted in Python |
- Can neural networks can learn to program synthesisers? |
- Compare neural networks against other optimisation techniques |

---

## Host VST in Python
<br>
- C++ JUCE Library hosts VST |
- Boost Python headers expose VST Host class to Python |
- Create better VST host in Python using exposed class |

---

## Use Python VST host
<br>
- Create whopping datasets |
- Biggest dataset had 1,771,561 examples |
- Each example is a pair of features and parameters |
- Tell the VST host which audio features you want |
- Parameters are the settings used to make the features |

---

## TensorFlow
<br>
- Split the datasets into Testing, Training, Validation |
- Create a network graph |
- Train the network|

---

## Visualising the results
<br>
- Save testing predictions in a datastructure |
- Sort by feature distance |
- MatPlotLib and Pandas for visualisation |

---

## Experiments
<br>
- Experimented with synthesisers |
- Experimented with features |
- Experimented with optimisation techniques |
- Experimented with reinforcement learning |
---

## Evaluations
<br>
<audio controls>
    <source src="assets/predicted_fm.wav"/>
</audio>
<audio controls>
    <source src="assets/actual_fm.wav"/>
</audio>
---

## Future
<br>
