# Gurrom Flow SMS API 🚀

Send SMS in seconds via a simple, reliable REST API.

✔ Fast integration  
✔ Built for transactional messaging  
✔ Scalable (350k+ SMS/month infrastructure)  
✔ South Africa-ready 🇿🇦  

---

## ⚡ Send Your First SMS in 60 Seconds

### Endpoint

POST https://api.flow.gurrom.co.za/api/messageapi/sendmessage

---

### 🔐 Authentication

Include your API key in the request header:

Authorization: Bearer YOUR_API_KEY

> Contact us to get your API key.

---

### 📤 Request

```json
{
  "AccountID": "YOUR_ACCOUNT_ID",
  "To": "27828703205",
  "MessageText": "Test from Gurrom Flow"
}

**### 📥 Response**

{
  "isSuccess": true,
  "messageStatus": "SUCCESS",
  "messageTrackingNumber": "3727691",
  "creditsAvailable": 76825
}
