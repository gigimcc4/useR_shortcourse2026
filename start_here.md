# R Project Setup - Pre-Workshop Instructions

## Welcome to the R You out of Memory Short Course!

We are so glad you will be joining us!

> **Before the workshop, please complete these setup steps.** This will ensure we can dive straight into working with big data during our session. This is the first part. Read the entire thing. You will need to grab another document and add it to the project folder.

✅ Complete setup first (this document)

✅ There's a second document coming (the Quarto workshop file)

✅ The second document goes into the project they're creating

So your workflow will be:

1.   **Pre-workshop:** Students follow the `.md` setup guide → create a project folder.

2.   **Pre-workshop:** You are provided the data download `.qmd` file → add it to their existing project folder.

3.   **Workshop begins:** Everyone has identical setup and can immediately start the actual big data work.

4.  **Additional Workshop:** You can get the rest of the Modules at the workshop directly from the github repository.

## What You'll Accomplish

By the end of this setup, you'll have:

✅ A properly organized R Project

✅ A 9GB real-world dataset downloaded and ready

✅ All necessary packages installed

✅ A workspace ready for big data analysis

## Time Requirements

-    **Setup time:** 5-10 minutes

-    **Download time:** 8-15 minutes (depends on your internet speed)

-    **Total time:** \~20 minutes

## Step 1: Create Your R Project

### Inside Using RStudio 

1.   Open RStudio

2.   Click **File** → **New Project**

3.   Choose **New Directory**

4.   Select **New Project**

5.   **Project directory name:** `useR2026_bigdata_shortcourse`

6.   Choose where to save it on your computer (somewhere you can easily find it!)

7.   Click **Create Project**

### Step 2: Verify Your Project Setup

Once your project is created, verify you're in the right place:

Open up a script file or QUarto file and run the following code

```{r}
# Check your current working directory
getwd() 

# List files in your project (should be empty for now) 
list.files()
```


