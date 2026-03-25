# 🏫 SchoolSphere - Modern School Management System

**SchoolSphere** एक अत्याधुनिक क्लाउड-आधारित (Cloud-based) प्लेटफॉर्म है जो स्कूलों, शिक्षकों, छात्रों और अभिभावकों को एक सुरक्षित और कुशल तरीके से जोड़ता है। यह प्रोजेक्ट शिक्षा प्रणाली को डिजिटल बनाने और स्कूल के संचालन को आसान बनाने के उद्देश्य से विकसित किया जा रहा है।

## ✨ मुख्य विशेषताएं (Key Features)

* **भूमिका-आधारित डैशबोर्ड (Role-based Dashboards):** एडमिन, प्रिंसिपल, शिक्षक और छात्रों के लिए अलग-अलग कस्टमाइज्ड इंटरफेस।
* **लाइव बस ट्रैकिंग (Live Bus Tracking):** Firebase Real-time Database (RTDB) का उपयोग करके स्कूल बस की रीयल-टाइम लोकेशन ट्रैक करने की सुविधा।
* **प्रवेश प्रबंधन (Admission Management):** नए छात्रों के लिए ऑनलाइन आवेदन और सुरक्षित डेटा स्टोरेज।
* **अटेंडेंस और फीस:** छात्रों की उपस्थिति और फीस रिकॉर्ड को डिजिटल रूप से मैनेज करना।
* **ऑफलाइन सपोर्ट:** खराब इंटरनेट में भी डेटा सुरक्षित रखने के लिए 'IndexedDB Persistence' का उपयोग।

## 🛠️ तकनीकी ढांचा (Tech Stack)

* **Frontend:** React.js, Tailwind CSS
* **Backend/Database:** Firebase Firestore & Real-time Database (RTDB)
* **Authentication:** Firebase Auth
* **Storage:** Firebase Storage (दस्तावेजों और रसीदों के लिए)

## 🚀 कैसे शुरू करें (Installation)

1.  रिपॉजिटरी क्लोन करें: `git clone https://github.com/schoolmanagement2030-cloud/SchoolSphere.git`
2.  `firebase.js` में अपनी **Firebase API Keys** अपडेट करें।
3.  `index.html` को किसी भी लाइव सर्वर या Netlify पर चलाएं।

## 🔒 सुरक्षा (Security)
यह प्रोजेक्ट **Firestore Rules** का उपयोग करता है ताकि डेटा केवल अधिकृत (Authorized) यूजर्स ही देख सकें और डेटा की अखंडता बनी रहे।

---
*Developed with ❤️ by Vikash*
