# Models

Small code simulations of biological mechanisms. Building a model is the strictest test of understanding: it forces me to state exactly what affects what, by how much and how quickly.

The models are meant to be **simple and wrong in known ways**, not clinically accurate.

## Conventions

- One folder per model, for example `models/temperature-regulation/`.
- Any language works. Python with `matplotlib` is an easy default for plotting how values change over time.
- Each model has a short `README.md` covering:
  - **What it represents:** the mechanism or loop
  - **Variables:** what is tracked, and what units
  - **Assumptions:** what has been simplified or left out
  - **What it predicts:** experiments to run (for example, "drop the volume by 20% and watch the heart rate")
  - **Where it's wrong:** known limits compared with the real body

## Ideas, roughly from simplest to hardest

1. **Body temperature regulation:** a set point, a sensor, and responses (sweating, shivering). A good first model of negative feedback. Also try what happens when the set point moves, as in a fever.
2. **Baroreflex:** the fast nerve reflex that corrects blood pressure after standing up.
3. **Blood volume and the kidneys:** the slow hormone and kidney loop that changes fluid volume over hours to days.
4. **Glucose and insulin:** two hormones pushing in opposite directions.
5. **Cardiac output and venous return (Guyton's model):** how the heart and blood vessels together settle on a steady circulation.
