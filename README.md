<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Integrated Database & Timetable</title>
    <style>
        body { font-family: Arial, sans-serif; margin: 40px; background-color: #f4f4f4; color: #333; }
        .container { max-width: 1000px; margin: 0 auto; }
        table { width: 100%; border-collapse: collapse; background: white; box-shadow: 0 4px 10px rgba(0,0,0,0.1); margin-top: 20px; }
        th, td { border: 1px solid #ddd; padding: 12px; text-align: left; }
        th { background-color: #004a99; color: white; text-transform: uppercase; font-size: 0.9rem; }
        tr:nth-child(even) { background-color: #f9f9f9; }
        h1 { color: #004a99; border-bottom: 2px solid #ccc; padding-bottom: 10px; }
        h2 { color: #555; margin-top: 30px; }
        .status-ontime { color: green; font-weight: bold; }
        .status-delayed { color: orange; font-weight: bold; }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <h1>Central Railway Station Schedule</h1>
            <hr>
        </header>

        <main>
            <section>
                <h2>Intercity Express Timings</h2>
                <table>
                    <thead>
                        <tr>
                            <th>Train ID</th>
                            <th>Name</th>
                            <th>Origin</th>
                            <th>Destination</th>
                            <th>Status</th>
                        </tr>
                    </thead>
                    <tbody>
                        <tr>
                            <td><b>TR-101</b></td>
                            <td><i>Blue Arrow</i></td>
                            <td>Station A</td>
                            <td>Station B</td>
                            <td class="status-ontime">On Time</td>
                        </tr>
                        <tr>
                            <td><b>TR-205</b></td>
                            <td><i>Night Rider</i></td>
                            <td>Station C</td>
                            <td>Station D</td>
                            <td class="status-delayed">Delayed</td>
                        </tr>
                    </tbody>
                </table>
            </section>

            <section>
                <h2>Student Database Records (Extracted from XML)</h2>
                <table>
                    <thead>
                        <tr>
                            <th>Student ID</th>
                            <th>Name</th>
                            <th>Course</th>
                            <th>Grade</th>
                            <th>City</th>
                        </tr>
                    </thead>
                    <tbody>
                        <tr>
                            <td>S001</td>
                            <td>Rahul Sharma</td>
                            <td>Computer Science</td>
                            <td>A</td>
                            <td>Mumbai</td>
                        </tr>
                        <tr>
                            <td>S002</td>
                            <td>Anjali Gupta</td>
                            <td>Information Tech</td>
                            <td>B+</td>
                            <td>Delhi</td>
                        </tr>
                        <tr>
                            <td>S003</td>
                            <td>John Doe</td>
                            <td>Electronics</td>
                            <td>A-</td>
                            <td>New York</td>
                        </tr>
                        <tr>
                            <td>S004</td>
                            <td>Sara Khan</td>
                            <td>Mathematics</td>
                            <td>A+</td>
                            <td>Bangalore</td>
                        </tr>
                        <tr>
                            <td>S005</td>
                            <td>Michael Tan</td>
                            <td>Physics</td>
                            <td>B</td>
                            <td>Singapore</td>
                        </tr>
                    </tbody>
                </table>
            </section>
        </main>

        <footer>
            <p style="margin-top: 40px; border-top: 1px solid #ccc; padding-top: 15px;">
                <strong>Note:</strong> <span>Please arrive <em>30 minutes</em> before departure.</span>
            </p>
        </footer>
    </div>
</body>
</html>
