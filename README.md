# Auto-Email-Generation
Auto Email Generation

# Run locally
- FastAPI server for backend
```
uvicorn lambda:app --host 127.0.0.1 --port 8000 --reload
```
- Fronted server
```
npm start
```
Other terminal npm start to start the react server

python-lambda-local -f handler lambda.py events.json