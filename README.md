# SCMS (System Club Management System)

### Structure for Writing Clean Code

#### **General Guidelines**
1. **Do Not Write Code in the `main` Method**
   - Ensure `main` is only used for initiating the program flow.
   
2. **Variable Naming**
   - Use **camelCase** for variable names.  
     Example: `clubSystem`

3. **Class, Interface, and Method Naming**
   - Use **Snake_Case** for class, interface, and method names.  
     Example: `Club_System`

4. **Comment and Explain Your Code**
   - Before defining any class, method, or interface, include your name and explain its purpose. Use the following format:
     ```java
     //// @Omar
     //// This class is responsible for "Explain"
     ```

5. **Use Full Words for Names**
   - Avoid abbreviations. Name everything in full for better readability.  
     Example: Use `membershipFee` instead of `mFee`.

6. **Separate Classes, Interfaces, and Methods**
   - Each class, interface, and method should be written in a new file to maintain clarity and modularity.

7. **Pre-Push Checklist**
   - Before pushing your code:
     - Verify there are no incomplete tasks or untested code.
     - Ensure the code is clean, formatted, and follows the structure above.

---

### Example Code Structure

**Club_System.java**
```java
//// @Omar
//// This class is responsible for managing club memberships
public class Club_System {
    private String clubName;

    public Club_System(String clubName) {
        this.clubName = clubName;
    }

    public String getClubName() {
        return clubName;
    }
}
