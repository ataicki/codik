1)  git clone https://github.com/ataicki/codik.git
2) cd codik
3) git submodule update --init --recursive
4) git submodule update --remote --merge
5) copy .env.example .env
6) docker compose up --build