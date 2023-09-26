## How to run the code?

### Step 1

Make sure your environment(or system) has libraries installed mentioned in requirements.txt.

**If not**, then use requirements.txt to install in the environment(or system).

### Step 2

run redis server by below command

redis-server

### Step 3

Use python to run the app.py file



run step 4 to 6 in different tabs/windows inside the environment

### Step 4

run Celery worker by below command

celery -A main.celery worker -l info

### Step 5

run celery Beat by below command
celery -A main.celery beat --max-interval 1 -l info

### Step 6

run mailHog fake SMTP



#### **Dummy User Details for fast access**:

username - **test**

password - **password**

