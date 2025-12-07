# Custom-scripts
Shell scripts I made for convenience.

### How to use them (MacOS)
1. Download the script
2. Open Terminal inside the same directory  
`chmod +x <script-name>`
3. Move the script to `/usr/local/bin/`  
`mv <script-name> /usr/local/bin/`
4. Run it

### Not Working? (Command Not Found)
1. Open your source file in code editor  
(Example: `.zshrc`, `.bashrc`)
2. Add `export PATH="$HOME/bin:$PATH"` to the end of the file