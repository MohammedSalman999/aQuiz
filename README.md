# aQuiz
Simple Quiz Program in Go: Reads a quiz from a CSV file and allows answering questions interactively.

### Hinglish:

**Go में सरल क्विज़ प्रोग्राम** **For English see below**

Yeh Go program CSV file se quiz padhta hai aur users ko command line ke through questions ke answers dene ki suvidha deta hai.

#### Usage:

1. **Installation:**
   - Apne computer mein Go install karein.

2. **Program chalana:**
   - Terminal kholen.
   - Apne Go program file (`main.go`) ke directory mein jaayein.
   - Niche diye gaye command se program chalayein:
     ```bash
     go run main.go -csv problems.csv
     ```
     `problems.csv` ko apni CSV file se replace karein jisme quiz questions aur answers hain.

3. **Flags:**
   - `-csv`: CSV file ka path specify karta hai. Default `problems.csv`.
   - `-limit`: Quiz ke liye time limit set karta hai. Default 30 seconds.

4. **Quiz format:**
   - Har line CSV file mein `question,answer` format mein honi chahiye.

5. **Example:**
   - Maan lijiye aapki `problems.csv` mein yeh hai:
     ```csv
     What is 2 + 2?,4
     What is the capital of France?,Paris
     ```
   - Program chalayein:
     ```bash
     go run main.go -csv problems.csv
     ```
   - Aapko set time limit ke andar har sawal ka jawab dene ke liye prompt milega.

#### Additional Notes:
- Yakeen karein ki aapki CSV file sahi tarah se format ki gayi aur accessible hai.
- Yeh program basic interactive quizzing ko support karta hai jisme customizable time limit hota hai.

---

### English:

**Simple Quiz Program in Go**

This Go program reads a quiz from a CSV file and allows users to answer questions interactively via the command line.

#### Usage:

1. **Installation:**
   - Make sure Go is installed on your computer.

2. **Running the Program:**
   - Open your terminal.
   - Navigate to the directory containing your Go program file (`main.go`).
   - Run the program using the following command:
     ```bash
     go run main.go -csv problems.csv
     ```
     Replace `problems.csv` with your CSV file containing quiz questions and answers.

3. **Flags:**
   - `-csv`: Specifies the path to the CSV file. Default is `problems.csv`.
   - `-limit`: Sets the time limit for the quiz. Default is 30 seconds.

4. **Quiz Format:**
   - Each line in the CSV file should be in the format `question,answer`.

5. **Example:**
   - Suppose your `problems.csv` contains:
     ```csv
     What is 2 + 2?,4
     What is the capital of France?,Paris
     ```
   - Running the program:
     ```bash
     go run main.go -csv problems.csv
     ```
   - You will be prompted to answer each question within the set time limit.

#### Additional Notes:
- Ensure your CSV file is correctly formatted and accessible.
- The program supports basic interactive quizzing with a customizable time limit.

---

Feel free to adjust the README file further to match your specific needs or preferences!
