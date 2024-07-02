# Getting Started
Deploy Ollama to Cloud Foundry for API test
- `mbt build`
- `cf deploy mta_archives/ollama_1.0.0.mtar`

## Next Steps
- Adjust Instance Memory and Instance Disk based on your requirements
- Click application URL in Cloud Foundry to check displaying `Ollama is running`
- Try to test `test-ollama.http` with REST Client. (before testing, set URL above to serviceUrl parameter)
- Currently there is no authentication (everyone can use Ollama), hence stop instance after you tested.

## Learn More
https://github.com/ollama/ollama/blob/main/docs/api.md
