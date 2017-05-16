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

## Methodologies
<br>
#### Host VST in Python
- C++ JUCE Library hosts VST |
- Boost Python headers expose VST Host class to Python |
- Create better VST host in Python using exposed class |

---

## Methodologies
<br>
#### Use Python VST host
- Create whopping datasets |
- Biggest dataset had **1,771,561** examples |
- Each example is a pair of features and parameters |
- Tell the VST host which audio features you want |
- Parameters are the settings used to make the features |

---

## Methodologies
<br>
#### TensorFlow
- Split the datasets into Testing, Training, Validation |
- Create a network graph
- Train the network

---

## Methodologies
<br>
#### Visualising the results
- Save testing predictions in a datastructure |
- Sort by feature distance |
- MatPlotLib and Pandas for visualisation |

## Results
<br>
---

## Evaluations
<br>
---

## Future
<br>
