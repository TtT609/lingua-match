# 📚 LinguaMatch
**A Lightweight Vocabulary Trainer & Language Memorizer**

LinguaMatch is a high-performance, browser-based application designed for mastering foreign language vocabulary. It features a streamlined interface for managing word lists and a gamified matching engine to reinforce long-term retention.

## ✨ Core Features
- **Multi-Language Optimization**: Specifically designed for Mandarin (Simplified/Traditional), Japanese (Kanji/Kana), Thai, and English.
- **Gamified Match Engine**: A dynamic testing environment where users must correctly identify both the pronunciation and meaning of words to maintain streaks and earn points.
- **Visual Recognition Settings**: Includes a font-switching system allowing users to toggle between standard "Computer" fonts and "Writing/Handwriting" patterns to help recognize characters in different styles.
- **Data Analytics**: A dedicated performance dashboard that tracks accuracy, best streaks, and identifies high-frequency error words for targeted review.
- **Bulk Data Management**: Supports CSV text import, file uploads, and UTF-8 BOM encoded CSV exports for seamless integration with external spreadsheet software like Excel.
- **Zero-Server Architecture**: Runs entirely client-side using browser `localStorage`, ensuring data privacy and offline accessibility.

## 🛠️ Technical Implementation
The application is built using a single-file architecture for maximum portability and zero-latency performance.
- **Frontend**: Responsive CSS3 with custom properties (CSS variables) and a dark-mode optimized "Tech-Industrial" UI.
- **Logic**: Pure Vanilla JavaScript (ES6+) handles state management, game cycles, and statistics calculation.
- **Data Handling**: Custom regex-based CSV parsing logic accommodates quoted fields and special characters.
- **Typography**: Dynamically loaded character sets via Google Fonts to ensure proper rendering of East Asian and Southeast Asian scripts.

## 🎮 How to Use
1. **Word Entry**: Add vocabulary via the "Word List" tab. You can manually enter words or import bulk lists via the CSV tools.
2. **Training**: Switch to the "Match Game" tab. The engine will queue your vocabulary and challenge you to find the correct pronunciation and definition pairs.
3. **Review**: Use the "Stats" page to monitor which words are causing the most errors and track your overall accuracy.
4. **Backup**: Use the "Export CSV" button to save your entire database as a local file.
