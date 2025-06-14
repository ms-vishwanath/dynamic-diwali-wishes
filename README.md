🎉 Diwali Greeting App – Next.js
A fun and personalized Diwali greeting app built with Next.js 13+ App Router that displays a custom message based on the name in the URL, along with animated cracker visuals using CSS.

<!-- Add a screenshot image of your page if available -->

✨ Features
🎊 Personalized "Happy Diwali" greeting using URL params

🧨 Animated firecracker visuals using custom CSS

🎨 Lightweight and responsive

🔡 Dynamic name capitalization and URL decoding

⚡ Built with React, Next.js, and TypeScript

🚀 Getting Started
1. Clone the repository
bash
Copy
Edit
git clone https://github.com/your-username/diwali-greeting-app.git
cd diwali-greeting-app
2. Install dependencies
bash
Copy
Edit
npm install
3. Run the development server
bash
Copy
Edit
npm run dev
Open http://localhost:3000/Alice in your browser to see the personalized greeting.

🔁 Usage
This app uses dynamic routing to personalize greetings:

arduino
Copy
Edit
http://localhost:3000/Alice
http://localhost:3000/Bob
The name in the URL is decoded and formatted

A custom message like “Happy Diwali Alice!” is rendered on the page

📂 Project Structure
python
Copy
Edit
app/
├── [name]/
│   └── page.tsx   # Main personalized greeting page
├── globals.css    # Cracker and layout styles
🛠 Tech Stack
Next.js

React

TypeScript

CSS Modules or Tailwind CSS (optional)# dynamic-diwali-wishes
