# Smart-Energy-Dashboard

### Prerequisites:
1. **Node.js and npm:** Ensure that you have Node.js and npm installed on your machine. You can download them from [https://nodejs.org/](https://nodejs.org/).

### Steps:

1. **Clone the Repository:**
   - Open your terminal or command prompt.
   - Navigate to the directory where you want to clone the project.
   - Run the following command to clone the repository:

     ```bash
     git clone <clone-link>
     ```


2. **Navigate to the Project Directory:**
   - Use the `cd` command to move into the project directory:

     ```bash
     cd your-repository
     ```

3. **Install Dependencies:**
   - Run the following command to install the project dependencies:

     ```bash
     npm install
     ```

4. **Build the Project:**
   - Run the build command to generate the necessary files:

     ```bash
     npm run build
     ```

5. **Start the App:**
   - After the build is successful, start the application:

     ```bash
     npm start
     ```
Before running the app, in a separate terminal in your project directory do the following
1. **Install `json-server` globally:**
   
   Open your terminal or command prompt and run:

   ```bash
   npm install -g json-server
   ```

2. **Run `json-server` with your `db.json` file:**

   Navigate to the directory containing your `db.json` file in your terminal and run:

   ```bash
   json-server --watch db.json --port 3000
   ```

   This command will start a server at `http://localhost:3000` using the data from your `db.json` file.
Certainly! Here are the steps to run a Next.js project from a GitHub repository on your local machine:


**Access the App:**
   - Open a web browser and navigate to [http://localhost:3000](http://localhost:3000) to view your running Next.js app.
