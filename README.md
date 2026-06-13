# PilibangaEmitra.com
<!DOCTYPE html>
<html lang="hi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>KPBPLB Online Hub | e-Mitra & Sarkari Form</title>
    <style>
        * { box-sizing: border-box; margin: 0; padding: 0; font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; }
        body { background-color: #f0f4f8; color: #333; line-height: 1.6; }
        a { text-decoration: none; color: #0056b3; font-weight: 500; }
        a:hover { text-decoration: underline; color: #ff4757; }

        /* Navigation Bar */
        header { background: #0a192f; color: white; padding: 15px 20px; position: sticky; top: 0; z-index: 1000; box-shadow: 0 4px 10px rgba(0,0,0,0.1); }
        .nav-container { display: flex; justify-content: space-between; align-items: center; max-width: 1200px; margin: auto; }
        .logo { font-size: 24px; font-weight: bold; color: #00ffcc; letter-spacing: 0.5px; }
        nav ul { display: flex; list-style: none; }
        nav ul li { margin-left: 20px; }
        nav ul li a { color: white; font-size: 15px; transition: 0.3s; }
        nav ul li a:hover { color: #00ffcc; }

        /* Top Banner */
        .hero { background: linear-gradient(135deg, #0a192f, #172a45); color: white; text-align: center; padding: 40px 20px; border-bottom: 4px solid #25d366; }
        .hero h1 { font-size: 32px; margin-bottom: 8px; color: #fff; }
        .hero p { font-size: 16px; color: #8892b0; }

        /* Layout Main Grid */
        .container { max-width: 1200px; margin: 25px auto; padding: 0 20px; display: grid; grid-template-columns: 2.2fr 1.2fr; gap: 25px; }

        /* Beautiful WhatsApp Form */
        .order-form { background: white; padding: 25px; border-radius: 12px; border: 1px solid #e2e8f0; box-shadow: 0 10px 15px -3px rgba(0,0,0,0.05); }
        .form-title { color: #25d366; margin-bottom: 20px; font-size: 22px; text-align: center; font-weight: bold; display: flex; align-items: center; justify-content: center; gap: 8px; }
        .form-group { margin-bottom: 18px; }
        .form-group label { display: block; margin-bottom: 6px; font-weight: 600; font-size: 14px; color: #4a5568; }
        .form-group input, .form-group textarea, .form-group select { width: 100%; padding: 11px; border: 1px solid #cbd5e1; border-radius: 6px; font-size: 14px; transition: 0.3s; background: #f8fafc; }
        .form-group input:focus, .form-group textarea:focus, .form-group select:focus { border-color: #25d366; outline: none; background: #fff; box-shadow: 0 0 0 3px rgba(37, 211, 102, 0.1); }
        .submit-btn { background: #25d366; color: white; width: 100%; padding: 14px; border: none; border-radius: 6px; font-size: 16px; font-weight: bold; cursor: pointer; transition: 0.3s; box-shadow: 0 4px 6px rgba(37,211,102,0.2); }
        .submit-btn:hover { background: #1ebd58; transform: translateY(-1px); }

        /* Links Tables */
        .table-box { background: white; border-radius: 8px; border: 1px solid #e2e8f0; overflow: hidden; box-shadow: 0 4px 6px rgba(0,0,0,0.02); margin-top: 25px; }
        .table-title { background: #0a192f; color: #00ffcc; text-align: center; padding: 12px; font-size: 16px; font-weight: bold; }
        .link-list { list-style: none; }
        .link-item { padding: 12px 15px; border-bottom: 1px solid #f1f5f9; display: flex; justify-content: space-between; align-items: center; font-size: 14px; }
        .link-item:last-child { border-bottom: none; }
        .tag-new { background: #ef4444; color: white; padding: 2px 6px; font-size: 11px; border-radius: 4px; font-weight: bold; }

        /* Sidebar Elements */
        .sidebar { display: flex; flex-direction: column; gap: 20px; }
        .box { background: white; padding: 20px; border-radius: 8px; border: 1px solid #e2e8f0; box-shadow: 0 4px 6px rgba(0,0,0,0.02); }
        .sidebar-title { font-size: 16px; color: #0a192f; border-bottom: 2px solid #00ffcc; padding-bottom: 6px; margin-bottom: 15px; font-weight: bold; }
        .service-grid { display: grid; grid-template-columns: 1fr 1fr; gap: 8px; }
        .service-card { background: #f8fafc; padding: 10px; text-align: center; border-radius: 6px; font-size: 13px; border: 1px solid #e2e8f0; font-weight: 500; }

        /* QR Code Box Style */
        .qr-box { text-align: center; }
        .qr-img { width: 170px; height: 170px; margin: 12px auto; border: 3px solid #25d366; padding: 5px; border-radius: 8px; background: #fff; }

        footer { background: #0a192f; color: #8892b0; text-align: center; padding: 20px; margin-top: 50px; font-size: 14px; border-top: 3px solid #00ffcc; }

        @media (max-width: 900px) {
            .container { grid-template-columns: 1fr; }
            .nav-container { flex-direction: column; gap: 10px; }
            nav ul li { margin: 0 10px; }
        }
    </style>
</head>
<body>

    <header>
        <div class="nav-container">
            <div class="logo">KPBPLB Online Hub</div>
            <nav>
                <ul>
                    <li><a href="#">होम</a></li>
                    <li><a href="#">ऑनलाइन फॉर्म</a></li>
                    <li><a href="#">रिजल्ट</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <div class="hero">
        <h1>KPBPLB ऑनलाइन फॉर्म & e-Mitra सेंटर</h1>
        <p>नीचे दिए गए फॉर्म को भरकर सीधे हमारे व्हाट्सऐप पर अपनी डिटेल्स भेजें।</p>
    </div>

    <div class="container">
        
        <!-- Left Side Form Area -->
        <div>
            <div class="order-form">
                <div class="form-title">📝 घर बैठे ऑनलाइन फॉर्म भरवाएं</div>
                <form id="whatsappForm">
                    <div class="form-group">
                        <label>आवेदक का पूरा नाम (Full Name):</label>
                        <input type="text" id="customerName" placeholder="अपना नाम लिखें" required>
                    </div>
                    
                    <div class="form-group">
                        <label>मोबाइल नंबर (WhatsApp Number):</label>
                        <input type="tel" id="customerPhone" placeholder="अपना मोबाइल नंबर लिखें" required>
                    </div>

                    <div class="form-group">
                        <label>जन्म तिथि (Date of Birth):</label>
                        <input type="date" id="customerDOB" required>
                    </div>

                    <div class="form-group">
                        <label>जाति वर्ग (Category):</label>
                        <select id="customerCategory" required>
                            <option value="">-- चुनें --</option>
                            <option value="General">General (सामान्य)</option>
                            <option value="OBC">OBC</option>
                            <option value="SC">SC</option>
                            <option value="ST">ST</option>
                            <option value="EWS">EWS</option>
                            <option value="MBC">MBC</option>
                        </select>
                    </div>

                    <div class="form-group">
                        <label>कौनसा कार्य या फॉर्म भरवाना है? (Select Service):</label>
                        <select id="formType" required>
                            <option value="">-- चुनें (Select Work) --</option>
                            <option value="Sarkari Bharti Form (All Job Forms)">सभी सरकारी नौकरी फॉर्म (All Job Forms)</option>
                            <option value="Admit Card / Result Work">एडमिट कार्ड / रिजल्ट संबंधित कार्य</option>
                            <option value="Mool Niwas Praman Patra">मूल निवास प्रमाण पत्र (Bonafide)</option>
                            <option value="Jati Praman Patra (Caste Certificate)">जाति प्रमाण पत्र (SC/ST/OBC/EWS)</option>
                            <option value="Income Certificate (Aay Praman Patra)">आय प्रमाण पत्र (Income Certificate)</option>
                            <option value="Jan Aadhaar Card Update/New">जनाधार कार्ड (नया/संशोधन)</option>
                            <option value="Pan Card New/Correction">नया पैन कार्ड / सुधार</option>
                            <option value="Aadhaar Card Download/Update">आधार कार्ड डाउनलोड / सुधार</option>
                            <option value="Voter ID Card Work">वोटर आईडी कार्ड संबंधित कार्य</option>
                            <option value="Ration Card Service">राशन कार्ड सर्विस</option>
                            <option value="Scholarship Form (Chhatravriti)">छात्रवृत्ति फॉर्म (Scholarship)</option>
                            <option value="Social Security Pension (Pension Work)">पेंशन फॉर्म / वार्षिक सत्यापन</option>
                            <option value="Chiranjeevi / Ayushman Bharat Yojana">आयुष्मान भारत / चिरंजीवी योजना</option>
                            <option value="Electricity / Water Bill Payment">बिजली / पानी बिल भुगतान</option>
                            <option value="Police Verification / Character Certificate">पुलिस वेरिफिकेशन (चरित्र प्रमाण पत्र)</option>
                            <option value="Other Online Work (अन्य कार्य)">अन्य कोई ऑनलाइन कार्य (Other Work)</option>
                        </select>
                    </div>

                    <div class="form-group">
                        <label>अतिरिक्त जानकारी / निर्देश (Message):</label>
                        <textarea id="customerMessage" rows="3" placeholder="यदि आपने 'अन्य कार्य' चुना है, तो काम का नाम यहाँ लिखें या कोई अन्य निर्देश दें..."></textarea>
                    </div>
                    
                    <p style="font-size: 12px; color: #666; margin-bottom: 12px;">* फॉर्म सबमिट करते ही आपकी डिटेल्स सीधे हमारे व्हाट्सऐप नंबर पर सेंड हो जाएगी।</p>
                    <button type="button" onclick="sendToWhatsapp()" class="submit-btn">🚀 व्हाट्सऐप पर डेटा भेजें</button>
                </form>