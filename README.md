# we-are-খাদক-2.0
সবাই মনে মনে হলেও আমরা প্রকাশ্যে খাদক, বাড়ী দানিগাটা বাদ জাবি ল একটা ও ফ্রী দাওয়াত😈
<!DOCTYPE html>
<html lang="bn">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>ইফতারির তথ্য</title>
  <style>
    body { font-family: Arial, sans-serif; margin: 20px; }
    input, select, textarea, button { width: 100%; margin: 5px 0; padding: 8px; }
    .entry { border: 1px solid #ccc; padding: 10px; margin: 10px 0; }
  </style>
</head>
<body>
  <h1>ইভেন্ট তথ্য আপলোড</h1>

  <h2>নতুন তথ্য জমা দিন</h2>
  <label>ধরন নির্বাচন করুন:</label>
  <select id="placeType" onchange="updateEventOptions()">
    <option value="">-- নির্বাচন করুন --</option>
    <option value="mosque">মসজিদের নাম</option>
    <option value="other">অন্যান্য</option>
  </select>

  <label>ঠিকানা লিখুন:</label>
  <input type="text" id="address" placeholder="ঠিকানা">

  <label>ইভেন্ট নির্বাচন করুন:</label>
  <select id="eventType">
    <option value="">-- নির্বাচন করুন --</option>
  </select>

  <label>তারিখ নির্বাচন করুন:</label>
  <input type="date" id
