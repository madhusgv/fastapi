Reference : https://www.youtube.com/watch?v=GN6ICac3OXY

1. Installation
    pip install fastapi
    pip install uvicorn
2. FastAPI Introduction 
    > is a modern, fast (high-performance), web framework for building APIs with Python 3.6+ based on standard Python type hints.
    > uvirocn or hypercorn is recomanded to deploy FastAPI
    > 
3. Async
    from fastapi import FastAPI
    app = FastAPI()

    @app.get("/api")
    async def root():
        await foo()
        return {"message": "Hello World"}
   > The async decorator makes the method async and 
4. user model

5. Host Django in Apache webserver
    https://www.youtube.com/watch?v=q__Nn0RRBvE
6. Host FastAPI in Apache webserver
    1. Use ASGI-WSGI Adapter
        https://www.infoworld.com/article/3629409/get-started-with-fastapi.html
7. Use reverse proxy of Apache to host FastAPI
    1. https://stackoverflow.com/questions/68181782/how-to-run-fastapi-on-apache2
