<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Play Prime - Admin Panel</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
  <style>
    body {
      background-color: #f8f9fa;
    }
    .sidebar {
      height: 100vh;
      background: #343a40;
      color: #fff;
      padding-top: 1rem;
    }
    .sidebar a {
      color: #adb5bd;
      display: block;
      padding: 0.75rem 1rem;
      text-decoration: none;
    }
    .sidebar a:hover {
      background: #495057;
      color: #fff;
    }
    .content {
      padding: 2rem;
    }
  </style>
</head>
<body>

<div class="container-fluid">
  <div class="row">
    <!-- Sidebar -->
    <nav class="col-md-2 d-none d-md-block sidebar">
      <h4 class="text-center">Admin Panel</h4>
      <a href="#">Dashboard</a>
      <a href="#">Orders</a>
      <a href="#">Products</a>
      <a href="#">Customers</a>
      <a href="#">Settings</a>
      <a href="#">Logout</a>
    </nav>

    <!-- Main content -->
    <main class="col-md-9 ms-sm-auto col-lg-10 content">
      <h2>Welcome, Admin!</h2>
      <p>This is your Play Prime admin dashboard. Use the sidebar to manage orders, products, and more.</p>

      <hr>

      <h4>Recent Orders</h4>
      <table class="table table-striped">
        <thead>
          <tr>
            <th>#Order ID</th>
            <th>Customer</th>
            <th>Status</th>
            <th>Total</th>
            <th>Date</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td>#001</td>
            <td>John Doe</td>
            <td>Processing</td>
            <td>₹1500</td>
            <td>2025-06-18</td>
          </tr>
          <tr>
            <td>#002</td>
            <td>Jane Smith</td>
            <td>Shipped</td>
            <td>₹2200</td>
            <td>2025-06-17</td>
          </tr>
        </tbody>
      </table>

    </main>
  </div>
</div>

<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>

</body>
</html>
📌 What’s included
✅ Clean sidebar navigation
✅ Responsive layout using Bootstrap 5
✅ Example “Recent Orders” table
✅ Ready to add real features (product uploads, order management, etc.)

⚡ How to use
Copy the code into a file named admin.html.

Open it in your browser.

Customize links and content as per your business.

For real use, connect it to a backend (like PHP, Node.js, or Firebase) and add authentication for security.

If you want, I can also:

Make a customer panel HTML

Provide a CSS file separately

Help you add login/logout functionality

Pack it in a ZIP for easy download

💡 Want me to prepare all that? Just say “Yes, prepare full files” and I’ll do it!










