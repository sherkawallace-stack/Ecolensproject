

#Ecolens
Final project for the Building AI course

## Summary
EcoLens – The AI Waste Sorter
My idea in a nutshell
EcoLens is a mobile-ready AI application designed to help users identify the correct recycling bin for their waste. By snapping a photo of an item, the AI classifies it as "Recyclable," "Compostable," or "Trash," reducing contamination in recycling streams.

Background
The Problem: Recycling rules are notoriously confusing and vary significantly by city. Many people throw non-recyclable items into the recycling bin (wish-cycling), which often results in the entire load being sent to a landfill.

Motivation: My motivation comes from seeing overflowing landfills and the frustration people feel when they want to be sustainable but don't know how.

Importance: Improving recycling accuracy is a low-cost way to reduce waste and lower the environmental footprint of communities.

Data and AI techniques
Data Sources: I plan to use the TrashNet dataset (a standard open-source dataset containing images of glass, paper, cardboard, plastic, metal, and trash) available on Kaggle.

AI Techniques:

I will use Convolutional Neural Networks (CNNs) to process the image data.

I plan to use Transfer Learning (using a pre-trained model like MobileNet) to ensure the application is fast enough to run on a smartphone.

I will use Python libraries like TensorFlow or PyTorch for the model development.

How is it used
Context: The primary user is a consumer at home or in an office setting, standing in front of their trash cans.

Impacted People: The solution affects consumers (who gain clarity), waste management facilities (who receive cleaner recycling streams), and the broader environment.

Viewpoints: It is important to consider that some users may have limited internet access or older smartphones, so the model must be lightweight and work offline if possible.

Challenges
Limitations: This project will not solve the issue of waste production itself—it only helps with sorting.

Complexity: AI models can struggle with dirty or crushed items, or items made of mixed materials (e.g., a coffee cup with a plastic lid). The model will have a lower accuracy rate for such items.

What next
Growth: In the future, this project could be integrated with location services to provide hyper-local recycling advice based on the user's specific city ordinances.

Expansion: It could potentially grow into an automated sorting bin for industrial use.

Acknowledgments
I want to acknowledge the creators of the TrashNet dataset for providing the foundational data.

Inspired by the open-source community on GitHub and tutorials from Fast.ai.

## Background




## How is it used?



## Data sources and AI methods


## Challenges


## What next?




## Acknowledgments
