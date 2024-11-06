# styletts2-api
Text-To-Speech Inference Server for StyleTTS2

## Usage

```
export API_KEY="your-secret-key-here"
docker compose up

curl -X POST "http://localhost:4321/generate" \
     -H "X-API-Key: your-secret-key-here" \
     -H "Content-Type: application/json" \
     -d '{"text": "Hello world"}'
```
