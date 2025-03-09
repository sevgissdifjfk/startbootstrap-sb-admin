# [Start Bootstrap - SB Admin](https://startbootstrap.com/template/sb-admin/)
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Modified SB Admin</title>
    <!-- Bootstrap CSS -->
    <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css" rel="stylesheet">
    <!-- Custom CSS -->
    <style>
        /* Global background color */
        body {
            background-color: #f8f9fc;
            font-family: 'Arial', sans-serif;
        }

        /* Sidebar custom styles */
        .sidebar {
            background-color: #4e73df; /* Blue background */
            color: white;
        }

        .sidebar .nav-link {
            color: white;
            font-size: 16px;
        }

        .sidebar .nav-link:hover {
            background-color: #2e59d9;
        }

        /* Navbar custom styles */
        .navbar {
            background-color: #333; /* Dark background */
        }

        .navbar .navbar-brand img {
            width: 120px;
        }

        /* Card section on dashboard */
        .card-header {
            background-color: #f8f9fc; /* Light background */
        }

        .card-body {
            padding: 25px; /* Extra padding */
        }

        /* Footer custom styles */
        footer {
            background-color: #2c3e50;
            color: white;
            padding: 15px;
            text-align: center;
        }

        /* Button custom styles */
        .btn-primary {
            background-color: #5a5a5a;
            border-radius: 8px; /* Rounded corners */
        }

        .btn-primary:hover {
            background-color: #333;
        }

        /* Chart custom styles */
        #myAreaChart {
            background-color: #ffffff;
            padding: 20px;
        }

        /* Profile image custom styles */
        .profile-img {
            border-radius: 50%;
            border: 2px solid #fff;
        }

        /* Form input fields */
        input, select, textarea {
            border: 2px solid #ddd;
            padding: 10px;
        }

        input:focus {
            border-color: #5a5a5a;
        }

        /* Custom section layout */
        .custom-section {
            background-color: #ffffff;
            padding: 30px;
            margin-top: 20px;
        }

        /* Adjust section titles */
        .custom-section h2 {
            color: #333;
        }
    </style>
</head>

<body>
    <!-- Sidebar -->
    <div class="sidebar">
        <div class="sidebar-header">
            <img src="https://via.placeholder.com/120" alt="Logo" class="navbar-brand">
        </div>
        <ul class="nav flex-column">
            <li class="nav-item">
                <a class="nav-link" href="#">Dashboard</a>
            </li>
            <li class="nav-item">
                <a class="nav-link" href="#">Reports</a>
            </li>
            <li class="nav-item">
                <a class="nav-link" href="#">Analytics</a>
            </li>
            <li class="nav-item">
                <a class="nav-link" href="#">Settings</a>
            </li>
        </ul>
    </div>

    <!-- Main Content Area -->
    <div class="main-content">
        <!-- Navbar -->
        <nav class="navbar navbar-expand-lg navbar-dark">
            <a class="navbar-brand" href="#">Modified SB Admin</a>
            <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav"
                aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ml-auto">
                    <li class="nav-item active">
                        <a class="nav-link" href="#">Home <span class="sr-only">(current)</span></a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">About</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Services</a>
                    </li>
                </ul>
            </div>
        </nav>

        <!-- Dashboard Cards -->
        <div class="container mt-4">
            <div class="row">
                <div class="col-xl-4 col-md-6 mb-4">
                    <div class="card shadow h-100 py-2">
                        <div class="card-header">
                            <h6 class="m-0 font-weight-bold text-primary">Dashboard Card 1</h6>
                        </div>
                        <div class="card-body">
                            <p>Here is some content for the first card. You can update the information as needed.</p>
                        </div>
                    </div>
                </div>
                <div class="col-xl-4 col-md-6 mb-4">
                    <div class="card shadow h-100 py-2">
                        <div class="card-header">
                            <h6 class="m-0 font-weight-bold text-primary">Dashboard Card 2</h6>
                        </div>
                        <div class="card-body">
                            <p>Here is some content for the second card. You can update the information as needed.</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>

        <!-- Custom Section -->
        <div class="custom-section">
            <h2>Recent Activities</h2>
            <ul>
                <li>User X logged in</li>
                <li>New message from Admin</li>
                <li>Comment added to a post</li>
            </ul>
        </div>

        <!-- Footer -->
        <footer>
            <p>&copy; 2023 Modified SB Admin. All rights reserved.</p>
        </footer>
    </div>

    <!-- Bootstrap JS and Dependencies -->
    <script src="https://code.jquery.com/jquery-3.3.1.slim.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.9.1/dist/umd/popper.min.js"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.js"></script>
</body>

</html>

Start Bootstrap is based on the [Bootstrap](https://getbootstrap.com/) framework created by [Mark Otto](https://twitter.com/mdo) and [Jacob Thorton](https://twitter.com/fat).

## Copyright and License

Copyright 2013-2023 Start Bootstrap LLC. Code released under the [MIT](https://github.com/StartBootstrap/startbootstrap-sb-admin/blob/master/LICENSE) license.
