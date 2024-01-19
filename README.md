# Gradio-FastAPI-Application

This is a demonstration of integrating FastAPI with Gradio to create and deploy an interactive web application. 

1. **Install Dependencies:**

   ```bash
   pip install fastapi uvicorn gradio
   ```

2. **Run the Application:**

   Run the following command in terminal:

   ```bash
   uvicorn run:app
   ```

   Output will look like this:

   ```
   INFO:     Started server process [46964]
   INFO:     Waiting for application startup.
   INFO:     Application startup complete.
   INFO:     Uvicorn running on http://127.0.0.1:8000
   ```

3. **Access the App:**

   - To view JSON statistics, open your web browser and go to [http://127.0.0.1:8000](http://127.0.0.1:8000).

   - To access the interactive gradio app UI, visit [http://127.0.0.1:8000/gradio](http://127.0.0.1:8000/gradio).

