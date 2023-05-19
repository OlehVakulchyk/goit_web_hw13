# goit_web_hw13
# verification and password reset


1. poetry shell
2. start docker container with postgres SQL
   and created BD web_hw11
3. # Setting up the alembic package
   alembic init alembic
   alembic revision --autogenerate -m 'Init'
   alembic upgrade head
4. # (optional)
   py goit_web_hw13/database/seeds.py
   # - to fill the database with fake data
5. py main.py
6. uvicorn main:app --host localhost --port 8000 --reload
7. http://127.0.0.1:8000/docs


