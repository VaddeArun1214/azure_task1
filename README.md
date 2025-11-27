
1. Clone the project and open it in VS Code.  
2. Installed Azure Functions Core Tools and Python 3.10+.  
3. Setuped `local.settings.json` with Cosmos DB endpoint, key, and database/container.  
4. Runned `pip install -r requirements.txt` inside the function app folder.  
5. Started the API locally using `func start`.  
6. Endpoints: POST, GET, PUT, DELETE under `/api/products`.  
7. Partition key in Cosmos DB must be `/id`.  
8. Use Postman or curl to test the CRUD operations.  
9. Deployed using `func azure functionapp publish <arunfunctionapp>`.  
10. Cosmos DB will store each products JSON document with fields id, name, price.
