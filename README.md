### Project Description
This project is a four-page HTML web form titled *Business Analytics Student Survey*. It collects basic demographic and academic data from students in the BAIS program at the University of Iowa. The form demonstrates proper use of HTML5, CSS3, and Bootstrap 5.3 to create an accessible, responsive, and user-friendly survey interface that follows modern design and accessibility standards.

---

### Best Practices for Forms
This web form follows several industry-recognized best practices for structure, usability, and validation. Each form field is clearly labeled and grouped logically, reducing cognitive load and helping users move smoothly through the input process. The `required` and `autofocus` attributes are implemented to guide users efficiently and prevent incomplete submissions. Dropdowns, radio buttons, and checkboxes are used where appropriate to simplify user decisions and ensure consistent, accurate data collection.

Bootstrap 5.3 classes and utility styles were used to standardize layout and provide a clean, professional appearance across all devices. The design employs consistent spacing, rounded buttons, and responsive containers to make the experience seamless on both desktop and mobile screens. A custom tooltip icon provides inline help without cluttering the interface—an example of a context-aware user-experience best practice that encourages comprehension while maintaining simplicity.

Each page maintains visual consistency through a shared header, footer, and University of Iowa logo. Semantic HTML elements such as `<fieldset>`, `<legend>`, and `<label>` enhance clarity and reinforce relationships between questions and their controls. These techniques make the form intuitive, aesthetically balanced, and compliant with web-form design principles that improve completion rates and reduce user error.

---

### Accessibility and Inclusion
Accessibility and inclusion were integrated into every step of this project in accordance with **WCAG 2.1 Level AA** and the principles discussed in class. The form is **perceivable** (content available through sight, hearing, or assistive technologies), **operable** (keyboard-friendly navigation with visible focus states), **understandable** (clear labels, logical grouping, and consistent structure), and **robust** (works across browsers, devices, and assistive tools).

Every input field uses semantic HTML with `<label>` and `for` attributes, enabling screen readers such as VoiceOver, NVDA, or ChromeVox to announce input purposes accurately. Text and background colors maintain a **contrast ratio of ≥ 4.5 : 1**, meeting W3C and WebAIM recommendations for readability. Icons and images include meaningful `alt` text or `aria-label` attributes so non-visual users receive the same information as sighted users.

In line with **ADA** and **Section 508** standards, the form also avoids unnecessary demographic questions.. Collectively, these features make the survey equitable, accessible, and user-friendly for students of all abilities and identities.
