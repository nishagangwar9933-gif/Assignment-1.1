<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Student Marksheet Table | Assignment 4.3</title>
</head>
<body>

  <!-- Page Header -->
  <header>
    <h1>Academic Examination Results &mdash; Semester I</h1>
    <p>Department of Computer Science &amp; Web Development</p>
  </header>

  <hr />

  <!-- Main Content -->
  <main>
    <section aria-labelledby="results-heading">
      <h2 id="results-heading">Student Marks Summary</h2>

      <table border="1" cellpadding="8" cellspacing="0">
        <!-- Table Title -->
        <caption>
          <strong>Semester I Student Marksheet (Maximum Marks: 100 per Subject)</strong>
        </caption>

        <!-- Table Head with rowspan and colspan -->
        <thead>
          <tr>
            <th scope="col" rowspan="2">Roll No.</th>
            <th scope="col" rowspan="2">Student Name</th>
            <th scope="colgroup" colspan="3">Subject Marks (Out of 100)</th>
            <th scope="col" rowspan="2">Total Marks (300)</th>
            <th scope="col" rowspan="2">Percentage</th>
            <th scope="col" rowspan="2">Grade</th>
          </tr>
          <tr>
            <th scope="col">HTML5 &amp; Web</th>
            <th scope="col">Mathematics</th>
            <th scope="col">Computer Fundamentals</th>
          </tr>
        </thead>

        <!-- Table Body: 5 Students & 3 Subjects -->
        <tbody>
          <tr>
            <td>101</td>
            <th scope="row">Aarav Sharma</th>
            <td>92</td>
            <td>88</td>
            <td>90</td>
            <td><strong>270</strong></td>
            <td>90.0%</td>
            <td>A+</td>
          </tr>
          <tr>
            <td>102</td>
            <th scope="row">Priya Verma</th>
            <td>85</td>
            <td>91</td>
            <td>84</td>
            <td><strong>260</strong></td>
            <td>86.7%</td>
            <td>A</td>
          </tr>
          <tr>
            <td>103</td>
            <th scope="row">Rohan Gupta</th>
            <td>78</td>
            <td>74</td>
            <td>82</td>
            <td><strong>234</strong></td>
            <td>78.0%</td>
            <td>B+</td>
          </tr>
          <tr>
            <td>104</td>
            <th scope="row">Sneha Yadav</th>
            <td>95</td>
            <td>94</td>
            <td>91</td>
            <td><strong>280</strong></td>
            <td>93.3%</td>
            <td>A+</td>
          </tr>
          <tr>
            <td>105</td>
            <th scope="row">Kabir Khan</th>
            <td>80</td>
            <td>83</td>
            <td>77</td>
            <td><strong>240</strong></td>
            <td>80.0%</td>
            <td>A</td>
          </tr>
        </tbody>

        <!-- Table Footer: Subject & Class Averages using colspan -->
        <tfoot>
          <tr>
            <th scope="row" colspan="2">Class Average Marks</th>
            <td><strong>86.0</strong></td>
            <td><strong>86.0</strong></td>
            <td><strong>84.8</strong></td>
            <td><strong>256.8</strong></td>
            <td><strong>85.6%</strong></td>
            <td>&mdash;</td>
          </tr>
        </tfoot>
      </table>
    </section>
  </main>

  <hr />

  <!-- Footer -->
  <footer>
    <p><small>Note: Passing marks require a minimum of 40% in each subject. &copy; 2026 Academic Examination Cell &mdash; Assignment 4.3</small></p>
  </footer>

</body>
</html>