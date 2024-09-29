<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Billing Website</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Billing System</h1>
    </header>
    <main>
        <section>
            <h2>Invoice</h2>
            <form id="billingForm">
                <label for="customerName">Customer Name:</label>
                <input type="text" id="customerName" required>

                <label for="amount">Amount:</label>
                <input type="number" id="amount" required>

                <label for="date">Date:</label>
                <input type="date" id="date" required>

                <button type="submit">Generate Invoice</button>
            </form>
        </section>
        <section id="invoiceOutput" style="display:none;">
            <h2>Invoice Summary</h2>
            <p id="summary"></p>
        </section>
    </main>
    <script src="script.js"></script>
</body>
</html>
