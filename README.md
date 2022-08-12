# Naming Conventions | Mr Yenagandula

### Naming Conventions In Detail
- The main intention of naming convention in javascript to write readable code. 
- Readable code is like understandble code. Meaning , if any one saw your code it is easy to understand and modify the code.
- Many people in current world , they are not mainitaining readable code.
- We have three building blocks in writing code.
    - Readability
    - Scalable 
      - Time Complexity
      - Space Complexity 
- Time Complexity is like execute the program quickly meaning write less code and create less number of variables so it will take less time.
- Space Complexity is like taking more space meaning creating more variables and more methods. 

### Naming Conventions with examples
 - Always give currect name to variable and that will be meaning full.

#### Recommanded and Good

```bash
const users=[];
const _users=[];
const defaultUsers=[];
const initalUsers=[];
const inActiveUsers = [];

```

#### Good only but not meaningful name

```bash
const u = []; 
const abcd = []; 
const Users = [];
```

#### For Plural give plural words only eg.users
```bash
const user = [];
```

#### Don't give your own names
```bash
const usersuers = []; 
```

#### bad if functionlity is related to users but u declared variable name as customers.
```bash
const customers = []; 
```

### Constant Variables
 - Constants are mainly used for static data or fixed values. 
 - We can use it for port number and data base queries etc.
 - If you want deal with constants please use sepate folder or module to delclare constants thats way u can use it for reusability.  
 - Constant variable names are always declared as capital letters
 
```bash
const USERS =[] 
const SELECT_USERS = 'SELECT * FROM USERS ';
const SELECT_USERS_BY_ID = 'SELECT * FROM USERS WHERE ID = ?';

```

### Types of variables 
- let (It is scope variable we can update the after initialization)
- const (It is scope variable we can't update the after initialization. It is for const values)
- var (IT is global scope variable we can update after initialization)

### Tips:
 - If variable declared and not using in ur project. 
 - Please remove those variables why because we are unnessary wasting our memory.
 - In java there is garbase collection is there and it will clean those variables.
 - For javascript you only clean that variable.

### In JavaScript
 - Varibles spaces will be allocated in heap memory.
 - Methods spaces will be allocated in stack memory.
