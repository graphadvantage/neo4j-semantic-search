# Neo4j Semantic Search

A minimal Streamlit application ready for deployment.

## Local Development

1. Install dependencies:
```bash
pip install -r requirements.txt
```

2. Run the app:
```bash
streamlit run app.py
```

## Deployment

### Streamlit Cloud

1. Push this repository to GitHub
2. Go to [share.streamlit.io](https://share.streamlit.io)
3. Connect your GitHub account
4. Select this repository
5. Set the main file path to `app.py`
6. Click "Deploy"

## Project Structure

```
.
├── app.py              # Main Streamlit application
├── requirements.txt    # Python dependencies
└── README.md          # This file
```

## Customization

- Modify `app.py` to add your search logic
- Add data connections (Neo4j, etc.)
- Update styling and layout as needed

## Built With

- [Streamlit](https://streamlit.io) - Web application framework
