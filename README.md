# go-environment-setup-directory-level


this is code for setup go language local folder level environment

download "go1.24.5.linux-amd64.tar.gz" for linux 
then open using below commad

cmd : tar -xzf go1.24.5.linux-amd64.tar.gz

which create current directory inside "go" name another directory

to run program 

cmd : ./go/bin/go run test.go

✅ (Optional) Alias for Convenience
To avoid typing ./go/bin/go every time, add a temporary alias:

cmd : alias g="./go/bin/go"

cmd : g run main.go

For a permanent alias, add it to ~/.bashrc or ~/.zshrc if you want.

🧠 Tip
You can also build it like this:

cmd : ./go/bin/go build main.go

This will create an executable named main.

▶️ How to Run the Built Executable
Simply run:

cmd :  ./main

If you see a permission denied error, give it execute permission:

cmd :  chmod +x main
cmd : ./main

You’ll see the output like:

Hello from Go!

🧠 Extra Tips
You can rename the output file during build:

cmd :  go build -o myapp main.go
cmd :  ./myapp

To clean up:

cmd : rm main
