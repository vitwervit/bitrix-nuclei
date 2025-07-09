# Bitrix nuclei templates
Typical Bitrix vulnerabilities

## Usage
1. Clone this repository to your local machine:
```bash
git clone https://github.com/vitwervit/bitrix-nuclei.git
cd bitrix-nuclei
```
2. Install nuclei if you haven't already. Refer to the [nuclei documentation](https://nuclei.projectdiscovery.io/docs/installation/) for installation instructions.
3. Run nuclei with the Bitrix templates on a list of targets specified in TARGETS.txt:
```bash\n"
nuclei -t . -l TARGETS.txt
```
Replace `TARGETS.txt` with your list of target URLs or IP addresses.
Or, you can run nuclei with the Bitrix templates on a specific URL:
```bash
nuclei -t . -u https://example.com
```

## Sources
- https://pentestnotes.ru/notes/bitrix_pentest_full/
