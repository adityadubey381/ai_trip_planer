# AI Trip Planner

A compact travel planning app with a Streamlit frontend and FastAPI backend. Enter a destination and trip length, and it returns a ready-to-use plan with:

- itinerary
- hotels
- restaurants
- activities
- transport options
- estimated costs
- weather and currency details


## Config

- config.yaml for model settings
- .env for API keys

This is a practical travel assistant built to generate useful trip plans quickly.

## all Command 
  -------------  

 ``` pip install uv ```

 ```uv init Ai_Trip_Planer```

 ```uv init```

```uv --version```

``` uv pythonlist ```

```uv pip list```

``` uv venv env --python cpython-3.12.6-windows-x86_64-none ```

```uv pip install langchain```

```uv add pandas```

```doskey/history```

## Run

```bash
uvicorn main:app --host 0.0.0.0 --port 8000 --reload
streamlit run streamlit_app.py
```