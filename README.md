# Token-Transfer-frontend(Next.js + Jotai + Tailwind CSS)

This is a frontend project for solana token transfer contract(Rust).

## Getting Started

- First, set your rust program id in `src/components/TokenTransfer.tsx`

    ```bash
    const PROGRAM_ID = "G73rpG7HAaPzJtEH3pzpkrY21t8rdMKkUv6Hry3GTcqs";
    ```

- Second, set your rust program idl in `src/idl/token_transfer.json`
    ```bash
    {
        "version": "0.1.0",
        "name": "token2022_transfer",
        "instructions": [
            {
                "name": "initialize",
                "accounts": [],
                ...
            }
    }
    ```


- Then, run the development server:

    ```bash
    npm run dev
    ```

- Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

## Auther
- [montedev0516](https://t.me/alpha_T0108)
