# flask auth with orcid

Demo of connecting to the orcid public api for use with the authorization grant code flow. This is not complete and is not intended for production use. It's just intended to demonstrate how one could begin this integration

Code is based off another example I will link to later when I can find it again. 

## quick start

First create client in orcid.org and set the client id and secret in your environment variables. You can use the example file `variables.sh` to do this.

```bash
source variables.sh

python3 -m venv venv && source venv/bin/activate

pip install -r requirements.txt

python app.py
```