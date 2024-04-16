# Fyle-internship-project
# Fyle Web Development Internship Challenge

## **Who is this for?**

This challenge is meant for candidates who wish to intern at Fyle and work with the Web Development team.

- You should be available full-time during the internship program (5 days a week).
- You should be available for 6 months of internship.

## **Why intern at Fyle?**

Fyle is a fast-growing Expense Management SaaS product (learn more about us [here](https://www.fylehq.com)). We are a ~40-strong engineering team at the moment. About 60% of our engineers started as interns. Interns at Fyle do extremely challenging and impactful work.

People love working at Fyle. Check out our Glassdoor reviews [here](https://www.glassdoor.co.in/Reviews/Fyle-Reviews-E1723235.htm). You can read stories from our teammates [here](https://stories.fylehq.com/).

## Challenge outline: Tax Calculator

Design a website that allows for tax calculation based on a users input.

![Screenshot 2024-04-07 at 12.06.20 AM.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/983632c5-ee66-4f64-a1a6-b3eeff04ddb8/b2775372-5b3a-462f-b309-5e3e512f457a/Screenshot_2024-04-07_at_12.06.20_AM.png)

![Screenshot 2024-04-07 at 12.06.37 AM.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/983632c5-ee66-4f64-a1a6-b3eeff04ddb8/24606b4a-5b8a-447c-8655-67dab0a7c472/Screenshot_2024-04-07_at_12.06.37_AM.png)

### References & Requirements

- The tax calculation works based on this formula -
    - Overall income (after deductions) under 8 (≤) Lakhs is not taxed.
        - Ex - if Gross Annual Income + Extra Income - Deductions =  6 Lakhs, no tax
        - if Gross Annual Income + Extra Income - Deductions =  9 Lakhs, tax
    - Income over 8 (>) Lakhs, the amount over 8 Lakhs is taxed at
        - 30% for people with age < 40
        - 40% for people with age ≥ 40 but < 60
        - 10% for people with age ≥ 60
        - Example
            - Age = 34, Income = 40 Lakhs, no deductions, tax = .3 * (40 - 8) = .3 * 32 = 9.6 Lakhs
- Do not restrict user from entering incorrect values like characters in the number fields
    - Highlight a error icon to the right of the input field (shown as an example in above image as a circle with `!`). Hovering over it should show the error in a tooltip
    - If no errors are present, dont show the error icon
    - This should be present in all the number fields
- The age dropdown field should have 3 values -
    - <40
    - ≥ 40 & < 60
    - ≥ 60
    - If user has not entered this value and clicks on submit, show a error icon hovering over which should show that input field is mandatory
- Error icons should not be visible in the form by default.
- Clicking on submit should show a modal which would show the final values based on above calculations.

### Notes

- The assignment has to be done in HTML, CSS and Javascript. You can use Bootstrap and Jquery but no other library/design system is allowed.
- You're free to make assumptions, please make sure they are mentioned in the README.
- Design is for representation purposes only, you are free to modify it, but all the functionalities as shown in the design (and as listed in requirements) should be present.
- Make sure all edge cases are thought out throughly and handled.

### Deliverables

- A Github repo link(public) of your solution, with a README to run and check things on local.
- Link to the hosted Web App.
- Screenshot of all tests passing inside the readme of the github repo that you submit.

## **Submission**

Please fill out this form with the details of the public link of the repository containing the application and test cases, the deployed application and your resume.

Also, 

Please record a video introducing yourself. 

<aside>
💡 Upload the video to Google Drive and share the public access link. Please verify if the video is visible to anyone with the link.

</aside>

We also want to hear your thoughts on your recently completed assignment. Keep the video under 2 minutes. Mention the following points in the video:

1. Introduce yourself. You can include:
a. Personal details like name, education, hobbies, etc.
b. Will you be available for a full-time internship for 6 months?
2. What was the most challenging part of the assignment?
3. If you were to change anything about the assignment, what would it be?

https://forms.gle/snPecXcVHaorq4768

## **What happens next?**

You will hear back from us via email within 2-3 days. We may request some changes based on reviewing your code.

Subsequently, we will schedule a phone interview with a Fyle Engineer.

If that goes well, we'll make an offer.

 

P.S. Please feel free to reach out to us if you have any questions, and remember to have fun with the assignment. :)
