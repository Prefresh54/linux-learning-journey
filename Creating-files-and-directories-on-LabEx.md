
# Linux Practice: File & Directory Basics

## Step 1: Ensure correct directory

Before proceeding, make sure you are in:
/home/labex/project

If not, use the cd command to navigate:
cd /home/labex/project

---

## Step 2: Create a new directory

We will create a folder called linux_practice.
mkdir linux_practice

### What mkdir does:
mkdir stands for Make Directory. It creates a new folder.

---

## Step 3: Move into the new directory
cd linux_practice

---

## Step 4: Create an empty file

We will create a file called hello.txt.
touch hello.txt

### What touch does:
- Creates an empty file if it does not exist
- Updates the timestamp if the file already exists

---

## Step 5: Confirm file creation

Use ls to list files:
ls

You should see:
hello.txt

---

## Extra Note: Redirection Operator

The > symbol is called a redirection operator.

It is used to send output into a file.

Example:
echo "Hello" > hello.txt

This writes "Hello" into hello.txt and overwrites existing content.
