# Certificate-Extractor
  Used OCR, Py2PDF and other tools..
---
```python
# Usage Example
logo_path = "SOA.png"
cert_path = "cert2.png"
present = verify_logo_in_certificate(logo_path, cert_path, debug=True)
print("RESULT:", "YES, logo present!" if present else "NO, logo not present.")
```
<img width="1106" height="680" alt="image" src="https://github.com/user-attachments/assets/a80e2908-2d14-4a41-a8a5-ecc14e7b7b5d" />
Logo detected by ORB feature matching.
RESULT: YES, logo present!
---
