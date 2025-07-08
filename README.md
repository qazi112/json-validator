# 🧰 json-cli-tool

A Python-based command-line utility to **validate**, **prettify**, and **minify** JSON — with optional output to file, clipboard support, and colorized terminal display.

---

## 🚀 Features

- ✅ Validate raw JSON or from file  
- ✅ Pretty-print (indent) JSON  
- ✅ Minify JSON to a compact format  
- ✅ Output to file  
- ✅ Copy to clipboard  
- ✅ Colorized JSON output using `rich`  
- ✅ Lightweight, simple, and fast

---

## 📦 Installation

Install via [PyPI](https://pypi.org/project/json-cli-tool/):

```bash
pip install json-cli-tool
```

---

## 💻 Usage

### ✅ Validate JSON from a file

```bash
json-cli --file data.json --validate
```

---

### 🎨 Pretty-print raw JSON string

```bash
json-cli --json '{"name":"Epic","type":"game"}' --pretty
```

---

### 🔧 Minify from a file and write to another

```bash
json-cli --file pretty.json --minify --output compact.json
```

---

### 🌈 Pretty-print with syntax highlighting

```bash
json-cli --file data.json --pretty --color
```

---

### 📋 Pretty-print and copy to clipboard

```bash
json-cli --file data.json --pretty --clipboard
```

---

## 🧪 Command-Line Options

| Flag           | Description                                      |
|----------------|--------------------------------------------------|
| `--json`       | Raw JSON string input                            |
| `--file`       | Path to a JSON file                              |
| `--validate`   | Check if JSON is valid                           |
| `--pretty`     | Format/indent JSON output                        |
| `--minify`     | Remove all whitespace from JSON                  |
| `--output`     | Write result to a specified file                 |
| `--clipboard`  | Copy result to system clipboard                  |
| `--color`      | Syntax highlight the output using `rich`         |

> ℹ️ One of `--json` or `--file` is required.

---

## 🛠 Dependencies

This tool requires the following Python packages:

- [`rich`](https://pypi.org/project/rich/) – for syntax-highlighted JSON output  
- [`pyperclip`](https://pypi.org/project/pyperclip/) – for clipboard integration

Install them manually if needed:

```bash
pip install rich pyperclip
```

---

## 🧑‍💻 Developer Info

- **Author**: Qazi Arsalan  
- **GitHub**: [https://github.com/qazi112/json-validator](https://github.com/qazi112/json-validator)  
- **PyPI**: [https://pypi.org/project/json-cli-tool/](https://pypi.org/project/json-cli-tool/)

---

## 📝 License

This project is licensed under the **MIT License**.  
See the full license text in the [`LICENSE`](LICENSE) file.

---

## 🙌 Contributions Welcome

Have an idea for improvement?  
Feel free to open issues, suggest features, or submit pull requests!

You can also fork the project and adapt it to work with:
- YAML
- XML
- TOML
- or any other structured data format!

Let’s build great tools — one line of JSON at a time.
