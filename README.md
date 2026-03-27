## 📌 The Problem: "Smart Spam"

Spam in India has evolved beyond simple English messages. Modern scammers use two main tricks to bypass traditional filters:

- **Language Hiding:** Messages are written in regional languages like Hindi, Telugu, and Bengali.  
- **Visual Hiding:** Spam content is embedded inside images or screenshots (e.g., fake bank alerts or lottery messages), which cannot be detected by text-only systems.  

---

## 💡 The Solution: A Triple-Check System

To detect this "Smart Spam," our system combines three AI components:

- **The Reader (NLP):**  
  Uses mBERT to understand the meaning of text across all four languages.  

- **The Vision (Computer Vision):**  
  Uses CLIP to analyze images and detect suspicious patterns (e.g., flashy "WINNER" signs or fake bank logos).  

- **The Scanner (OCR):**  
  Uses EasyOCR to extract text from images so it can be analyzed by the NLP model.  

- **The Decision Maker (Fusion):**  
  A smart layer that combines text and image insights to produce a final, highly accurate prediction.  

---

## 📊 The Dataset: Diverse & Fast

- **4 Languages:** English, Hindi, Telugu, and Bengali  
- **Real-World Images:** Includes screenshots and spam flyers, not just plain text  
- **Few-Shot Learning:** A fast-learning approach that achieves high accuracy even with limited data  

---

## 📈 The Results

The system successfully detects spam even when:

- The message exists only inside an image  
- The message is a mix of English and regional languages (Hinglish, Telugish, etc.)  
- The spam relies on visual cues alone to mislead users  
