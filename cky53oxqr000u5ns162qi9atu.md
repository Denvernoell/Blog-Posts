## Unit Convertor

I don't know how you typically do unit conversions. You may have all the ones that you use often memorized, you may have a reference sheet or Excel file that you use, you may look it up every time. Depending on what you use or how complicated your conversion is can determine how easy it is for somebody else to determine what units you are converting to and how you get there. There are online unit convertors that you can use to convert from volume to volume or weight to weight, but not always from flow rate to flow rate (a common occurrence in water resources) or other complex units. The unit convertor I created uses the **[Pint](https://pint.readthedocs.io/en/stable/)** module to convert between units and the **[Streamlit](https://docs.streamlit.io/)** module to create a GUI. 
[![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://share.streamlit.io/denvernoell/akel_units/main/akel_units.py)

Notes:
- Magnitude on *From* is optional, whereas magnitude on *To* is not allowed (my preference is to leave both without magnitude)



