# Productive Peer Finder

A simple C-based console application that helps users find like-minded peers based on responses to a set of 12 questions related to coding interests, career goals, and tech preferences.

## 💡 Features

- Adds users by taking their name and survey responses.
- Saves user data persistently to `users.txt`.
- Calculates similarity score between users.
- Matches a user with their top 3 most similar peers.
- Saves match results to `matches.txt`.

## 📋 Questions Asked

Users answer the following on a scale of 1 to 5:

1. How much do you agree that you have actively built or contributed to coding projects?
2. How much are you aiming to get a remote job in the future?
3. How strongly do you dream of working at top companies like Google or Microsoft?
4. How interested are you in exploring Web Development further?
5. How much do you enjoy working with electronics or hardware components?
6. How interested are you in joining or attending a coding bootcamp?
7. How interested are you in pursuing a Master’s degree abroad?
8. How seriously are you considering or preparing for the GATE exam?
9. How often do you watch tech-related or programming content on YouTube?
10. How passionate have you always felt about Computer Science?
11. How much was your choice to study Computer Science influenced by your family?
12. How confident do you feel about your coding skills at this stage?

## 🧠 Matching Algorithm

- Calculates similarity between two users as:
  

- Converts score into a percentage and ranks potential matches from highest to lowest.

## 🗃️ File Descriptions

- `users.txt`: Stores user names and their responses.
- `matches.txt`: Appends match results after each session.

## 📦 How to Use

1. **Compile the code:**
 ```bash
 gcc peer_finder.c -o peer_finder

 🎯 Purpose: A  project for peer networking utility to connect users with similar aspirations.