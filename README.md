# Financial Learning & Analysis Platform

Our website is designed to make learning and utilizing financial statements both easy and fun. 

## 📌 Problem Statement

**Balance sheets and income statements** are essential for understanding a company’s financial health. However, many employees struggle with financial interpretation, leading them to avoid reviewing these documents. Our platform simplifies the process by offering two core features: an interactive analysis tool and a guided learning experience, helping users become proficient in financial analysis with ease.

## ⭐ Key Features

### 1. Analysis Tool

- **Drag & Drop Interface**
    
    Easily input key financial statement data, such as balance sheets and income statements, via CSV or Excel files. If the file is not in one of these formats, it will be assumed to be an image.
    
- **Visual Data Generation**
    
    Automatically convert your data into visual charts and graphs that highlight essential financial metrics.
    
- **Comparative Analysis**
    
    Quickly and intuitively compare data across different periods or categories to support informed decision-making. 
    

### 2. Interactive Learning Game

- **Foundational Concept Learning**
    
    Learn the basics of balance sheets and financial metrics through a variety of interactive challenges.
    
- **Game-Based Learning**
    
    Designed with beginners in mind, our engaging and interactive game maximizes your learning experience.
    

## 🚀 Setting Up UgaHacks & FinCompare  

Follow these steps to get everything running smoothly!  



1. ** Clone & Run the Frontend**  
```sh
git clone https://github.com/lukasp-dev/ugaHacks.git
cd ugaHacks
npm i
npm run dev
```
Your frontend will be live at **http://localhost:5173** 🎉  



2. ** Retrieve the Secret Sauce (.env) for Backend**  
Head over to **[this secret vault](https://send.bitwarden.com/#xgNiTrXvF0CZVrJ_AMKM-Q/NsdjiLz8ip6hpn-SPw_mtg)** 🔐  
- You’ll need a **magic word** to unlock it 🧙‍♂️  
- Think **"the name of this hackathon"**, all lowercase 😉

Once inside, copy the **.env** file contents.



3. ** Clone & Run the Backend**  
```sh
git clone https://github.com/lukasp-dev/FinCompare.git
cd FinCompare
```
- Create a `.env` file in the root directory and **paste** the secret contents.  

Then, install dependencies & start the server:  
```sh
npm i
node server.js
```
Your backend will be live at **http://localhost:8080** 🚀  


## 🚩 Getting Started

1. **Visit the Website** 
    
    Go to [Website URL] and start exploring.
    
2. **Sign Up and Log In** 
    
    Register quickly and gain instant access to both the Analysis Tool and the Learning Game.
    
3. **Input and Analyze Data** 
    
    Use our drag & drop feature to input your financial data and experience the power of visual and comparative analysis.
    
4. **Upload Financial Statements**
    - You can upload balance sheets and income statements for up to 5 companies. Each company can have financial data for multiple years.
    - Once an image is uploaded, the system will parse the data and auto-fill the respective fields. Users should verify that the extracted data matches their original files before proceeding.
5. **View Data Visualizations**
    - After confirming the uploaded data, clicking the ‘Next’ button will generate eight different visualizations.
        - Balance Sheet Comparison: Bar chart and line chart comparing balance sheet components across companies.
        - Income Statement Comparison: Bar chart and line chart comparing income statement components across companies.
        - Balance Sheet Financial Data Analysis: Bar chart displaying balance sheet data for a single company over multiple years.
        - Income Statement Financial Data Analysis: Bar char displaying income statement data for a single company over multiple years.
        - Financial Ratios: Key calculated ratios presented per company.
        - EBITA: A dedicated chart displaying EBITDA calculations.
    - These visualizations provide users with a comprehensive financial analysis of their balance sheet and income statement data.
6. **Utilize the Learning Game**
    - If interpreting the generated charts proves challenging, it may indicate a lack of foundational financial knowledge. The Learning Game helps users build this understanding.
    - Selecting the game section will present 10 randomly selected questions from the following categories.
        - Definition-based questions testing fundamental financial concepts.
        - Interpretation questions assessing the ability to analyze economic indicators.
        - Calculation questions requiring users to compute financial metrics based on given balance sheet and income statement data.
            - For this calculation-based questions, hints about relevant formulas will be provided.

## 🖥️ Tech Stack

### 🌐 Frontend
  ![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
  ![Chart.js](https://img.shields.io/badge/Chart.js-FF6384?style=for-the-badge&logo=chartdotjs&logoColor=white)
  ![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
  ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
  ![Axios](https://img.shields.io/badge/Axios-5A29E4?style=for-the-badge&logo=axios&logoColor=white)

### 🛠 Backend & Database 
  ![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
  ![Express.js](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)
  ![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)

### ☁️ Cloud & API
  ![AWS S3](https://img.shields.io/badge/AWS%20S3-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white)
  ![MongoDB Atlas](https://img.shields.io/badge/MongoDB%20Atlas-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
  ![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)


## 🙋‍♂️ Future Steps

1. **Enhance Data Integration**
    - Support additional financial statement formats such as cash flow statements.
2. **Expand Learning Game Content**
    - Introduce advanced financial analysis scenarios.
    - Enhance engagement by incorporating features such as avatar customization and competitive elements among users.
3. **Introduce Collaborative Features**
    - Create a discussion platform where users can engage in financial report analysis and exchange insights.
