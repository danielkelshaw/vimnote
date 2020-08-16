# vimnote

## **Installation:**

Clone the repository and change directory:

```bash
git clone https://github.com/danielkelshaw/vimnote
cd vimnote
```

Add the `src` directory to your path:

```bash
echo "export PATH=\$PATH:$(pwd)/src" >> ~/.zshrc
```

## **Making Notes:**
You can make a note by calling:

```bash
note Example Note
```

This will create a note at `/path/to/directory/notes/DD-MM-YYYY.md` and open in `vim`:

```
# [HH:MM] Example Note
<cursor>
```

## **Search Notes:**
In order to search through existing notes, use the command:

```bash
search
```

A list of the headers for all existing notes will be shown - allowing you to search through with `fzf`.
<br> The chosen file is opened at the relevant line in `vim`.

