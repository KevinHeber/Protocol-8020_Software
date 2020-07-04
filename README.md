# Protocol-8020_Software
Protocol-8020 Software

Repository for organizing the documentation and software components.

Package 1 -- Personal Profile: GUI with a long list of personal data such as age, height, weight, BMI, gender, family disease known, inheritable disease, etc.
  Storage format is XML using Numeric Identifiers & English Labels.  The GUI may support localization.
Package 2 -- Disease Profile: Using a variety of Open Source tools, create the disease profiles from public data resources.
  Storage format is XML as described elsewhere.
Package 3 -- CLI, Text or GUI interface that computes the Disease Risk Matrix and displays the results.  For each listed disease, what is the calculated risk.
  Reads the XML files, does the math, outputs with optional localization.

These are not complex tasks.  Package 1 is mostly just a data entry and validation package.  Package 2 will require the most research and assembly because of the number of diseases (infectious and otherwise).  Package 3 is just doing the math - nothing fancy.  Package 3 has the most risk of "Feature Bloat" since the GUI can do more manipulation with the incoming data and visualizations.  See R (Statistical Package) for ideas.
