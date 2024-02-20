# Questionnaire-Analysis-Automation

This script created in order to automate the analysis of data generated from questionnaires. While working on a market research company and analyzing various questionnares daily, I realised that there are repetitive steps that could be automated and save a  lot of time.

In general there are two categories of questions in a questionnaire:
- Those who have a **single answer** (simple questions)
- Those who can have **multiple answers** (multiple questions)

Each of these category requires a different approach to be analyzed appropriately.

Independently the category of question it is common that we want to calculate the **distribution of the answers of the question** and to display the **crosstabulation between this question and another one** (for example with demographics)

Also another thing to consider is the **distinction between ordered and no-ordered questions**.
Ordered questions are those whose their answers have a particular order (for example days, months, consumption frequency, likert etc).

No ordered are those whose the order does not matter. For example "which is your favourite brand?"
In this case, we want to display the answers in increasing order.
