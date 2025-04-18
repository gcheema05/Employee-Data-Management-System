<h1>👥 Employee Data Management System</h1>

<p>
A Java-based desktop application for managing employee data using object-oriented programming and GUI components built with AWT and Swing. This system streamlines employee record handling with features like creation, modification, sorting, and file-based persistence—all via an intuitive graphical interface.
</p>

<hr />

<h2>📌 Problem Statement</h2>
<p>
Efficiently managing employee records can become increasingly difficult as the data grows. Manual tracking is error-prone and lacks scalability. This project provides an automated solution through a Java GUI-based system where employee information can be added, edited, and stored with ease.
</p>

<hr />

<h2>✅ Solution</h2>
<p>
This GUI application includes three primary views:
</p>
<ul>
  <li><strong>Register View</strong> – New users can register; data is saved to a file.</li>
  <li><strong>Login View</strong> – Authenticates users against saved credentials.</li>
  <li><strong>Main View</strong> – Allows users to:
    <ul>
      <li>Insert new employee records</li>
      <li>Delete existing employees</li>
      <li>Edit employee details</li>
      <li>Search for employees</li>
      <li>Sort employee records</li>
      <li>Save employee data to a user-defined file</li>
      <li>Read employee data from a specified file</li>
    </ul>
  </li>
</ul>

<p>
Employee information is displayed in a table format, showing:
</p>
<ul>
  <li>First Name</li>
  <li>Last Name</li>
  <li>Address</li>
  <li>Phone Number</li>
  <li>Employee ID (randomly generated)</li>
  <li>Type of Employee (Hourly, Manager, Sales)</li>
  <li>Hiring Date</li>
  <li>Annual Earnings</li>
</ul>

<hr />

<h2>🛠 Tech Stack</h2>
<table>
  <tr><td><strong>Language</strong></td><td>Java</td></tr>
  <tr><td><strong>GUI Framework</strong></td><td>AWT, Swing</td></tr>
  <tr><td><strong>IDE</strong></td><td>Eclipse</td></tr>
  <tr><td><strong>JDK Version</strong></td><td>Java 8 or higher</td></tr>
</table>

<hr />

<h2>👨‍💻 Collaborators & Contributions</h2>
<ul>
  <li><strong>Gurbaaz</strong>
    <ul>
      <li>Created <code>Employee</code> base class and <code>EmployeeList</code> class</li>
      <li>Enabled inheritance for Manager, SalesEmployee, and HourlyEmployee classes</li>
      <li>Assisted in developing the MainScreen GUI</li>
    </ul>
  </li>
  <li><strong>Nawaf</strong>
    <ul>
      <li>Developed Register screen GUI</li>
      <li>Created Login screen GUI</li>
      <li>Implemented file handling logic (save/load functionality)</li>
    </ul>
  </li>
  <li><strong>Sandesh</strong>
    <ul>
      <li>Built <code>Manager</code>, <code>SalesEmployee</code>, and <code>HourlyEmployee</code> subclasses</li>
    </ul>
  </li>
</ul>

<hr />

<h2>📥 How to Download and Run</h2>

<h4>🔧 Requirements</h4>
<ul>
  <li>Java Development Kit (JDK)</li>
</ul>

<h4>📦 Steps</h4>
<pre><code>
# Clone the repository
git clone https://github.com/gcheema05/Employee-Data-Management-System

# Navigate to the project directory
cd Employee-Data-Management-System

# Compile the project
javac -d bin src/*.java

# Run the application
cd bin
java LoginView
</code></pre>

<hr />

<h2>🚀 Future Enhancements</h2>
<ul>
  <li>🔒 Add password encryption for secure login</li>
  <li>📊 Integrate charting tools to visualize employee data</li>
  <li>📱 Improve GUI responsiveness and layout</li>
  <li>🌐 Add export/import support for JSON/CSV</li>
  <li>🔎 Advanced filtering and search capabilities</li>
</ul>
