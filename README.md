# Test

* https://github.com/FredHutch/stlite-template

Maybe use as a template instead of github fork.

Use Test Data

* Venkatesh et al, preprint - https://github.com/flu-crew/h1-risk-pipeline

> StreamlitAPIException: The default value of 1000 must lie between the min_value of 1000 and the max_value of 46, inclusively.

* [ ] Requires some pre-processing (set empty to 0, set "<10" to 10 or 5).

## Steps

1. [x] Copy a template repository on GitHub
2. [ ] Adding your Streamlit app
    1. [ ] Place all your Python/streamlit code in the file `app.py`
    2. [ ] Add any libraries whcih are imported by the app in line 25 of `index.html`
    3. [ ] If you have any `@st.cache` decorators in your streamlit app, add the argument `show_spinner=False`
    4. [ ] Ask the user to upload the file directly using the [streamlit file uploader utility](https://docs.streamlit.io/library/api-reference/widgets/st.file_uploader)
3. [x] Testing locally `streamlit run app.py`
4. [ ] Deploying publicly to the web with GitHub Pages
