# boilerplate for next.js + fastapi + postgres
 

## Database

```bash
docker-compose up
```

## Backend

Setup

```bash
cd backend
python -m venv venv
. venv/bin/activate
pip install -r requirements.txt
```

Run the development server

```bash
uvicorn main:app --reload
```


## Frontend


Install dependencies

```bash
cd frontend
npm install

```

Run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `pages/index.tsx`. The page auto-updates as you edit the file.

