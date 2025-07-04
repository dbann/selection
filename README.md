# Missing-Data / Selection-Bias Visualizer
Interactive one-page demo that **shows, in real time, how different missing-data mechanisms could bias regression**.  
Move the sliders, watch β̂ diverge from the truth, and build intuition about MCAR vs MNAR in seconds.

**▶️ [Live demo](https://dbann.github.io/selection/)**

![Demo](selection_demo.gif)

## Features
- **Percent-missing slider** plus presets for MCAR, MNAR-by-X, MNAR-by-Y, `X ∨ Y`, *Flatten* and *Steepen*.
- Live read-outs of **β<sub>true</sub>**, **β̂**, and a colour-coded bias gauge.
- One-click **resample** to illustrate sampling variability.
- Single HTML file 

## How was this made?
With AI!  'vibe coding' - that is, giving the idea to an AI (LLM) and asking it to implement it. I used a combination of LLMs (GPT, claude, gemini), and worked iteratively untill a reasonably useful tool was created - sometimes the LLMs make mistakes (errors, unwanted features etc). It was then hosted on github. 

## License
MIT License - see the [LICENSE](LICENSE) file for details.

## Feedback
david.bann@ucl.ac.uk 
