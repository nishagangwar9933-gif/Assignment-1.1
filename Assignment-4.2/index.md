<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Job Application Form | Assignment 4.2</title>
</head>
<body>

  <!-- Page Header -->
  <header>
    <h1>TechNova Web Solutions &mdash; Careers</h1>
    <p>Complete the job application form below to apply for an open position on our engineering team.</p>
  </header>

  <hr />

  <!-- Main Form Content -->
  <main>
    <section aria-labelledby="application-heading">
      <h2 id="application-heading">Job Application Form</h2>

      <form action="#" method="post">

        <!-- Section 1: Personal Information -->
        <fieldset>
          <legend><strong>1. Personal Information</strong></legend>

          <!-- Disabled Field Example -->
          <p>
            <label for="application-id">Application Reference ID (Auto-Generated):</label><br />
            <input
              type="text"
              id="application-id"
              name="application_ref_id"
              value="APP-2026-8492"
              disabled
            />
          </p>

          <!-- Full Name -->
          <p>
            <label for="full-name">Full Name: *</label><br />
            <input
              type="text"
              id="full-name"
              name="full_name"
              placeholder="Enter your full name"
              required
            />
          </p>

          <!-- Email -->
          <p>
            <label for="applicant-email">Email Address: *</label><br />
            <input
              type="email"
              id="applicant-email"
              name="email"
              placeholder="you@example.com"
              required
            />
          </p>

          <!-- Phone -->
          <p>
            <label for="applicant-phone">Phone Number: *</label><br />
            <input
              type="tel"
              id="applicant-phone"
              name="phone"
              placeholder="e.g., 9876543210"
              pattern="[0-9]{10}"
              title="Enter a 10-digit phone number"
              required
            />
          </p>

          <!-- Date of Birth -->
          <p>
            <label for="dob">Date of Birth: *</label><br />
            <input
              type="date"
              id="dob"
              name="date_of_birth"
              required
            />
          </p>

          <!-- Portfolio URL -->
          <p>
            <label for="portfolio-url">Portfolio or GitHub URL:</label><br />
            <input
              type="url"
              id="portfolio-url"
              name="portfolio_url"
              placeholder="https://github.com/yourusername"
            />
          </p>
        </fieldset>

        <br />

        <!-- Section 2: Role, Shift & Skills -->
        <fieldset>
          <legend><strong>2. Role Preferences &amp; Technical Skills</strong></legend>

          <!-- Dropdown for Job Role -->
          <p>
            <label for="job-role">Applying For (Job Role): *</label><br />
            <select id="job-role" name="job_role" required>
              <option value="">-- Select a Job Role --</option>
              <option value="frontend-intern">Front-End Web Developer Intern</option>
              <option value="junior-ui-developer">Junior HTML/CSS UI Developer</option>
              <option value="fullstack-trainee">Full-Stack Web Engineering Trainee</option>
              <option value="qa-accessibility-tester">Web Accessibility &amp; QA Tester</option>
            </select>
          </p>

          <!-- Radio Buttons for Preferred Shift (Same 'name' attribute) -->
          <p>
            <span><strong>Preferred Work Shift: *</strong></span><br />
            <input
              type="radio"
              id="shift-morning"
              name="preferred_shift"
              value="morning"
              required
            />
            <label for="shift-morning">Morning Shift (9:00 AM &ndash; 5:00 PM)</label><br />

            <input
              type="radio"
              id="shift-evening"
              name="preferred_shift"
              value="evening"
            />
            <label for="shift-evening">Evening Shift (2:00 PM &ndash; 10:00 PM)</label><br />

            <input
              type="radio"
              id="shift-flexible"
              name="preferred_shift"
              value="flexible"
            />
            <label for="shift-flexible">Flexible / Remote Hours</label>
          </p>

          <!-- Checkboxes for Skills -->
          <p>
            <span><strong>Technical Skills (Select all that apply):</strong></span><br />
            <input type="checkbox" id="skill-html" name="skills" value="HTML5" />
            <label for="skill-html">Semantic HTML5</label><br />

            <input type="checkbox" id="skill-css" name="skills" value="CSS3" />
            <label for="skill-css">CSS3 &amp; Responsive Design</label><br />

            <input type="checkbox" id="skill-js" name="skills" value="JavaScript" />
            <label for="skill-js">JavaScript Basics</label><br />

            <input type="checkbox" id="skill-git" name="skills" value="Git & GitHub" />
            <label for="skill-git">Git &amp; GitHub Version Control</label>
          </p>
        </fieldset>

        <br />

        <!-- Section 3: Cover Letter & Submission -->
        <fieldset>
          <legend><strong>3. Cover Letter &amp; Submission</strong></legend>

          <!-- Textarea for Cover Letter -->
          <p>
            <label for="cover-letter">Cover Letter / Why Should We Hire You?: *</label><br />
            <textarea
              id="cover-letter"
              name="cover_letter"
              rows="5"
              cols="50"
              placeholder="Write a brief cover letter highlighting your projects, skills, and interest in this role..."
              required
            ></textarea>
          </p>

          <!-- Submit & Reset Buttons -->
          <p>
            <button type="submit">Submit Application</button>
            <button type="reset">Reset Form</button>
          </p>
        </fieldset>

      </form>
    </section>
  </main>

  <hr />

  <!-- Footer -->
  <footer>
    <p><small>* Required fields. Note: Disabled fields (such as Application Reference ID) are read-only and excluded from form submission. &copy; 2026 TechNova Web Solutions.</small></p>
  </footer>

</body>
</html>