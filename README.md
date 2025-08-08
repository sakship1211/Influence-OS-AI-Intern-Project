 InfluenceOS – LinkedIn AI Branding Assistant 

 Features

- ✅ AI-generated LinkedIn posts (via GPT or prefilled content)
- ✅ Editable profile and brand tone
- ✅ Content calendar simulation
- ✅ Post performance analytics
- ✅ JSON export of generated content
- ✅ Clean React UI simulation (mock frontend)

 Project Structure

InfluenceOS_Submission/
├── InfluenceOS_SakshiPathak_Complete.ipynb       # Main notebook
├── requirements.txt                               # Python dependencies
├── README.md                                      # This file
├── frontend/                                      # Optional React UI
│   ├── App.js                                     # React component
│   └── README.md                                  # UI instructions
├── PDFs/
│   ├── User_Guide.pdf
│   ├── Technical_Report.pdf
└── sakshi_linkedin_post.json                      # Output data

 How to Run (Python / Jupyter)

1. ✅ Install Python ≥ 3.10  
2. ✅ Install Jupyter:
   
   pip install notebook
   
3. ✅ Install dependencies:
 
   pip install -r requirements.txt
   
4. ✅ Launch notebook:

   jupyter notebook
   
5. ✅ Open `InfluenceOS_SakshiPathak_Complete.ipynb`  
   Follow cell-by-cell execution to:
   - Generate post (via OpenAI or offline)
   - Simulate content calendar
   - Simulate analytics
   - Export to `.json`

 How to Run Frontend (Optional UI)

If you want to test the mock React UI:

1. Open `frontend/` in VS Code  
2. Run:
   ```bash
   npx create-react-app .
   npm install -D tailwindcss postcss autoprefixer
   npx tailwindcss init -p
   ```
3. Update `tailwind.config.js`:
   ```js
   content: ["./src/**/*.{js,jsx,ts,tsx}"],
   ```
4. Replace `src/App.js` with the provided code  
5. Replace `src/index.css` with:
   ```css
   @tailwind base;
   @tailwind components;
   @tailwind utilities;
   ```
6. Start:
   ```bash
   npm start
   ```

 Dependencies

Install Python dependencies with:
```bash
pip install -r requirements.txt
```

```
openai>=1.0.0
tiktoken
notebook
langchain>=0.2.0     
```

