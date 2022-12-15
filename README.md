# json-server-videos

Example in memory videos api with json-server

# Installation

```bash
git clone https://github.com/Noormohammad011/rtk-query-server.git
cd directory_name
npm install
npm start
```

Now opens:

- http://localhost:9000

You now have a full REST API. Test with POSTMAN or any other REST Client):

Retrieve all (GET):

```bash
GET http://localhost:9000/videos
```

Retrieve one (GET):

```bash
GET http://localhost:9000/videos/1
```

Post a todo (POST):

```bash
POST http://localhost:9000/videos text="Rtk-query" completed=false color="red"
```

Update todo (PUT):

```bash
PUT http://localhost:9000/3 name="Rtk-query" completed=true color="green"
```

Delete todo (DELETE):

```bash
DELETE http://localhost:9000/videos/1
```

