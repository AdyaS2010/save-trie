# Trie-Based Dog Names Storage

## Description
This project is a trie-based storage system for popular dog names written in C. It reads dog names from a file, stores them in a trie data structure, and allows users to check if a name is in the trie. The program also includes functionality to unload the trie from memory.

## Features
- Store dog names in a trie data structure
- Check if a dog name is in the trie
- Unload the trie from memory

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/trie-dog-names.git
   ```
2. Navigate to the project directory:
   ```bash
   cd trie
   ```
3. Compile the code:
   ```bash
   make trie
   ```

## Usage
1. Run the application:
   ```bash
   ./trie infile
   ```
   Replace `infile` with the path to the input file containing the dog names.

## Example
```bash
$ ./trie dog_names.txt
Check word: Bella
Found!
```

![image](https://github.com/user-attachments/assets/6fe98f63-54a9-488b-a6db-5ea372bd643c)

![image](https://github.com/user-attachments/assets/315825ea-649d-4025-bdef-6769eeffa913)

![image](https://github.com/user-attachments/assets/c14f14d6-377c-4837-9f44-7f56b010edc5)

*After reading in an infile (in args/command as the first line in running a program), for example names.txt, a series of words (in a dictionary, txt, file, etc.), in this case, dog names for reference, you will be able to query a certain word and get a response as to whether it is present and found in that file!* 

## Contributing
1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature/your-feature-name
   ```
3. Make your changes and commit them:
   ```bash
   git commit -m 'Add some feature'
   ```
4. Push to the branch:
   ```bash
   git push origin feature/your-feature-name
   ```
5. Open a pull request.

## License
This project is not licensed under any License currently.
