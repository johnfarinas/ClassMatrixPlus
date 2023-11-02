# Guide

 1. git clone https://github.com/johnfarinas/Student-Performance-Analytics.git
 2. Go to Student-Performance-Analytics Folder. [cd Student-Performance-Analytics] using git bash or power shell.
 3. npm install
 4. npm run dev
 5. edit tailwind.config.js with the code below
 
            const withMT = require("@material-tailwind/react/utils/withMT");
            
            module.exports = withMT({
              content: ["./index.html", "./src/**/*.{vue,js,ts,jsx,tsx}"],
              theme: {
                extend: {},
              },
              plugins: [],
            });

 7. 