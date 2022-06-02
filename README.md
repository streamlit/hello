# Demo: `streamlit hello` as a native multipage app

[![Open in Streamlit](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://share.streamlit.io/streamlit/hello/main/Hello.py)
This project highlights Streamlit's new multipage app functionality. 

![In-use Animation](https://github.com/streamlit/demo-face-gan/blob/master/GAN-demo.gif?raw=true "In-use Animation")

## How to run this demo
The demo can be access via [Streamlit Community Cloud](https://streamlit.io/cloud)[here](https://share.streamlit.io/streamlit/hello/main/Hello.py) or locally via the following steps:

```
pip install streamlit
streamlit hello
```

## Model Bias 

Playing with the sliders, you _will_ find biases that exist in this model. For example, moving the `Smiling` slider can turn a face from masculine to feminine or from lighter skin to darker. Apps like these that allow you to visually inspect model inputs help you find these biases so you can address them in your model _before_ it's put into production.

## Questions? Comments?

Please ask in the [Streamlit community](https://discuss.streamlit.io) or [check out our article](https://towardsdatascience.com/build-an-app-to-synthesize-photorealistic-faces-using-tensorflow-and-streamlit-dd2545828021).
