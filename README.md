**Objective:** Capture and update user input dynamically.  
- **Task:** Create a text input field and show real-time changes.  
- **Pseudo Code:**  
Step 1: const [input, setInput] = useState("")
Step 2: Create input field → value={input}, onChange={e => setInput(e.target.value)}
Step 3: Display <p>{input}</p> below input box
Step 4: As user types, text updates instantly
<img width="1718" height="960" alt="Screenshot 2025-09-24 135933" src="https://github.com/user-attachments/assets/b9a49645-16cc-4f78-9238-bb8bf2f79fcd" />
