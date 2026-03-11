# Contributing to DiaGuard

Thank you for your interest in making diabetes care accessible across India!

## How to Contribute

1. Fork the repository
2. 2. Clone your fork: git clone https://github.com/YOUR_USERNAME/diaguard.git
   3. 3. Create a branch: git checkout -b feature/your-feature-name
      4. 4. Make your changes
         5. 5. Commit: git commit -m "feat: your feature description"
            6. 6. Push and open a Pull Request against main
              
               7. ## Development Setup
              
               8. ### Backend (Flask)
               9. pip install -r backend/requirements.txt
               10. flask run
              
               11. ### Frontend (React + Tailwind)
               12. cd frontend
               13. npm install
               14. npm run dev
              
               15. ### Firmware (ESP32)
               16. - Install Arduino IDE
                   - - Open firmware/main.ino
                     - - Select board: ESP32 WROOM-32
                       - - Install libraries: ArduinoJson, BLEDevice
                        
                         - ## Pull Request Guidelines
                        
                         - - Keep PRs focused and small
                           - - Include unit tests for new backend logic
                             - - Update README if you add a new feature
                               - - All ML changes must include SHAP explanation validation
                                 - - Clinical data handling must follow HIPAA-aligned standards
                                  
                                   - ## Reporting Bugs
                                  
                                   - Open a GitHub Issue with steps to reproduce and expected vs actual behavior.
                                  
                                   - ## License
                                  
                                   - MIT License
