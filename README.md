# AutomATAhon2024-Experience
Sharing my experience at AutomATAhon 2024.

# My Journey Through AutomATAhon 2024: A Test Automation Challenge

I am thrilled to share my incredible experience participating in **AutomATAhon 2024**, a prestigious competition for test automation professionals sponsored by the Global Testing Retreat (GTR). This was my first time competing in such a large and challenging event, which provided not only an opportunity to test my skills but also immense learning about the industry and my standing as a professional. Although I couldn’t progress beyond the first round, the experience was a valuable learning opportunity that emphasized the importance of continuous growth.

## Competition Overview
- **Total Duration:** 8 hours
  - **Test Execution:** 4 hours
  - **Demo Presentation:** 4 hours
- **Participants:** 11 teams
- **Rounds:**
  - Round 1: November 23, 2024
  - Round 2: December 8, 2024
# Challenges and Scoring
The competition was designed to test participants on a wide range of test automation skills across UI, API, and desktop environments. It was divided into Challenge A and Challenge B, with the former being mandatory for proceeding to the latter. Challenge B was accessible only to those who completed Challenge A.

# Challenge A: Total Marks - 265
	1. Set up Library in Koha (UI) — 5 marks
	2. Create a Librarian (Library UI) — 20 marks
	3. Patron Creation (Multiple Methods) — 30 marks
		○ OPAC UI
		○ Librarian UI
		○ API
	4. Validate Patron Login — 10 marks
	5. Cataloging: Create and Validate Books and Items — 40 marks
	6. Multi-browser Parallel Validation — 40 marks
	7. Add and Hold Books — 30 marks
	8. Issue and Validate Book Status Across Interfaces — 20 marks
	9. Add Credits to Patron Using API — 20 marks
	10. Submit or Check-in Books — 10 marks
	11. Validate Returned Books in OPAC — 10 marks
	12. Search and Validate Holdings Availability — 10 marks
	13. Book Cover Image Comparison — 30 marks
# Challenge B: Total Marks - 100
	1. Desktop App Automation — 50 marks
	2. Web App Automation — 30 marks
	3. Koha API Automation — 20 marks

# Key Tasks and My Approach
	1. Login and Setup
		○ Using Selenium WebDriver, I automated the login process to the Koha application and initialized the library setup with the given credentials and specified parameters.
	2. Patron and Librarian Management
		○ Leveraged REST Assured for API automation to create patrons programmatically.
		○ Validated the patron creation across different interfaces (OPAC UI, Librarian UI, and API) and ensured all were successfully logged in.
	3. Cataloging and Book Management
		○ Automated cataloging tasks, including adding books and validating their availability in multiple browser sessions.
		○ Used parallel browser execution to ensure real-time synchronization across interfaces.
	4. Advanced Functionalities
		○ Implemented a custom function to add credits via API for logged-in patrons and validated the updated credit balance in UI interfaces.
		○ Automated the issue, return, and status validation of books to ensure seamless end-to-end workflows.
	5. Visual Validation
		○ Compared book cover images using image processing libraries to validate accuracy in OPAC UI.

# Lessons Learned and Takeaways
	1. Importance of Pre-Work
		○ Setting up reusable base functions for handling UI elements, API calls, and multi-browser support saved significant time during execution.
	2. Multi-Browser Challenges
		○ Managing synchronization and validation in parallel browser environments was one of the toughest yet most rewarding aspects of the competition.
	3. API and UI Integration
		○ Combining API and UI automation to handle patron management and credit updates highlighted the need for seamless integration between layers.
	4. Validation as a Core Principle
		○ Each task required thorough validation to ensure the correctness of automated workflows.

# My Opinion on the Challenges
	• The competition required meticulous preparation, especially for handling foundational aspects like Excel readers, property files, and reusable functions.
	• Most tasks relied on Selenium WebDriver for UI automation, while API-related functionalities were efficiently handled using REST Assured.
	• The emphasis on multi-browser scenarios reinforced the importance of robust parallel execution strategies.
	

# Final Thoughts
Participating in AutomATAhon 2024 was an exhilarating experience that tested my abilities and expanded my knowledge. It showcased the importance of adaptability and preparedness in test automation while providing a platform to connect with like-minded professionals.
If you’re passionate about test automation and love solving complex challenges, I highly recommend giving AutomATAhon a shot. It’s not just a competition but a journey of learning and growth.

What are your thoughts on such competitions? Have you participated in one? Share your experiences in the comments below!

