
# 🌍 Smart Tourist Assistant - Mini Expert System

A simple expert system built using **Prolog** that helps users find ideal travel destinations based on their **region**, **interests**, **budget**, and **preferred travel season**.

> 🎓 Developed as a group mini project for  
> **COU4201 – Knowledge Representation and Logic Programming**  
> **Open University of Sri Lanka**

---

## 📌 Project Overview

Planning a trip can be time-consuming and confusing, especially when trying to match a destination to personal preferences. This mini expert system aims to solve that by recommending destinations based on user input.

The system uses a **knowledge base of destinations** and applies logical rules to suggest places that match:

- Travel region (e.g., Europe, Asia)
- Interests (e.g., culture, nature, food)
- Budget level (low, medium, high)
- Travel season (summer, winter, etc.)

---

## 🛠️ Technologies Used

- **SWI-Prolog**
- Logic-based expert system principles
- Text-based user interface

---

## 🚀 How to Run

1. Install [SWI-Prolog](https://www.swi-prolog.org/Download.html).
2. Clone this repository:
   ```bash
   git clone https://github.com/your-username/smart-tourist-assistant.git
   cd smart-tourist-assistant
   ```
3. Open SWI-Prolog and consult the smart_tourist_assistant.pl file.
4. Start the program by typing:
   ```prolog
   start.
   ```

---

## 🧠 How It Works

The system interacts with the user through a text-based interface:

- Asks 4 questions: region, interests, budget, and season.
- Uses rules like `allowed_budgets/2` to filter matching destinations.
- Uses Prolog’s pattern matching and `intersection/3` to compare user interests with available destinations.
- Prints matching results using Prolog’s backtracking mechanism to show multiple recommendations.

---

## 📦 Features

✅ Text-based interactive travel assistant  
✅ Intelligent matching logic  
✅ Supports multiple interests and seasons  
✅ Customizable knowledge base  
✅ Budget filtering (low/medium/high)  
✅ Easy to expand with new destinations

---

## 🤖 Sample Interaction

```
=============================================================
        SMART TOURIST ASSISTANT - Mini Expert System         
=============================================================

We will help you find the perfect travel destination!

Please answer the following questions:

1. What is your preferred region to travel?
   europe | america | africa | asia | oceania

2. What are your interests? (as a list, e.g. [culture, food] or any)
   adventure | art | beach | city_life | culture | food | nature | party | relaxation | water_sports | wildlife

3. What is your budget level?
   low | medium | high

4. What is your preferred travel season?
   spring | summer | autumn | winter | any
```

---

## 👥 Group Members (Group No: 24)

– S.K.S Silva  
– W.R.N. Silva  
– M.S.N.K. Salgado  
– N.A.S. Sewwandi  
– T.A.B.T. Samadhini  
– S.D.T. Rupasinghe  
– K.H.M.R.S. Wijerathne  

---

## 🧩 Future Improvements

- Accept user input without square brackets for interests.
- Expand the knowledge base with more destinations.
- Add a graphical user interface (GUI).
- Integrate real-time weather or travel cost APIs.

---

## 📄 License

This project is for academic use only.

---

## 📬 Feedback

Feel free to submit issues or suggestions in the [Issues](https://github.com/RuchiraSilva/smart-tourist-assistant/issues) tab.
