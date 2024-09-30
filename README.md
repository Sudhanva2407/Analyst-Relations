# Analyst-Relations
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Crypto Regulation Categories</title>
    <style>
        body {
            font-family: Calibri, sans-serif;
        }

        .main-box {
            width: 80%;
            background-color: #002060; /* Dark blue background */
            padding: 20px;
            margin: 0 auto;
            display: grid;
            grid-template-columns: repeat(3, 1fr); /* 3 boxes per row */
            gap: 20px;
        }

        .small-box {
            background-color: #b4c6e7; /* Light blue shade */
            padding: 20px;
            border: 1px solid #004085;
            color: black;
            position: relative;
            text-align: center;
            font-weight: bold;
            cursor: pointer;
            transition: background-color 0.3s ease;
        }

        .small-box:hover {
            background-color: #d6e0f5; /* Lighter blue on hover */
        }

        .small-box p {
            font-weight: normal;
        }

        /* Pop-up box */
        .popup {
            visibility: hidden;
            width: 300px;
            background-color: #f9f9f9;
            color: black;
            text-align: left;
            padding: 10px;
            border: 1px solid #0070C0;
            position: absolute;
            z-index: 1;
            top: 100%;
            left: 50%;
            transform: translateX(-50%);
            box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.1);
        }

        .small-box:hover .popup {
            visibility: visible;
        }
    </style>
</head>
<body>

<div class="main-box">
    <!-- Box 1 -->
    <div class="small-box">
        AML/CFT Laws
        <div class="popup">
            These regulations aim to eliminate illicit financial activity by requiring financial institutions to monitor and report suspicious behavior.
        </div>
    </div>

    <!-- Box 2 -->
    <div class="small-box">
        Crypto Taxation
        <div class="popup">
            Is taxation applied on crypto players? This includes tax on income and capital gains as well as corporate taxes.
        </div>
    </div>

    <!-- Box 3 -->
    <div class="small-box">
        Consumer Protection
        <div class="popup">
            This can be in the form of advertising regulations, data storage and privacy, transfer rules, cybersecurity, investor accreditation, etc.
        </div>
    </div>

    <!-- Box 4 -->
    <div class="small-box">
        Travel Rule
        <div class="popup">
            The Travel Rule, implemented by the FATF, requires financial institutions to share data on transactions beyond a threshold.
        </div>
    </div>

    <!-- Box 5 -->
    <div class="small-box">
        Licensing Requirements
        <div class="popup">
            Do businesses and investors have licensing disclosure and reporting requirements, regulated by regulatory authorities?
        </div>
    </div>

    <!-- Box 6 -->
    <div class="small-box">
        Asset Classification
        <div class="popup">
            A standardized approach to categorizing crypto assets based on their characteristics, such as functionality, use case, and regulatory status.
        </div>
    </div>

    <!-- Box 7 -->
    <div class="small-box">
        Crypto ETFs
        <div class="popup">
            Allows investors to gain exposure to crypto through a regulated and easily accessible investment vehicle.
        </div>
    </div>

    <!-- Box 8 -->
    <div class="small-box">
        CBDCs
        <div class="popup">
            Stages a country is in with respect to CBDC – R&D, Pilot, Launched, Cross Border Projects, Cancelled.
        </div>
    </div>

    <!-- Box 9 -->
    <div class="small-box">
        Stablecoins
        <div class="popup">
            Ensures stability and transparency by enforcing reserve backing, audits, and oversight to protect users and maintain financial stability.
        </div>
    </div>

</div>

</body>
</html>

![image](https://github.com/user-attachments/assets/bbafae0e-eef9-4154-9cf0-d7b00db1a7f5)
