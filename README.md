# Introduction to Explainable AI

This full-day course provides an introduction to the topic of Explainable AI (XAI). This fundamental knowledge is to be used as a starting point for self-guided learning during and beyond the course time. All course days cover alternating sequences of theoretical input and hands-on exercises, which are discussed with the instructors during the course.

The goal of the course is to help participants understand how XAI methods can help uncover biases in the data or provide interesting insights. After a general introduction to XAI, the course goes deeper into state-of-the-art model agnostic as well as model-specific interpretation techniques. The practical hands-on sessions will help to learn about strengths and weaknesses of these standard methods used in the field.

## Venue
The course will be onsite: TP Conference Center, INF 582, Heidelberg

## Schedule at a glance

#### XAI for Random Forest

|    Time     |       Session       |
|-------------|---------------------|
|09:00 - 09:30| Introduction to eXplainable AI (XAI) |
|09:30 - 10:00|	Permutation Feature Importance |
|10:00 - 10:30| LIME |
|10:30 - 10:45| Break |
|10:45 - 11:45| SHAP|
|11:45 - 12:30| FGC |
|12:30 - 13:30| Lunch Break|
|13:30 - 15:30|	Hand-On Session |
|15:30 - 16:00| Conclusions & Wrap-up |

LINK TO SURVEY: https://forms.office.com/pages/responsepage.aspx?id=k-Qp4vIbp0CbhIX2wjru2CUg8imPeZhDs5ZKG7PYKGFUNVNYTE9EWEJDTzUxU1dYTzlZNDMxRVdUVy4u&route=shorturl

## Mentors

- [Dr. Lisa Borros de Andrade e Sousa](mailto:lisa.barros@helmholtz-munich.de), Helmholtz Munich
- [Dr. Donatella Cea](mailto:donatella.cea@helmholtz-munich.de), Helmholtz Munich


## Requirements and Setup

This course assumes you have minimal experience running Python and Machine Learning Frameworks like sklearn.

It is possible to either create an environment and install all the necessary packages locally (using the requirements.txt file) or to execute the notebooks on the browser, by clicking the 'Open in Colab' button. This second option doesn't require any further installation, but the user must have access to a Google account.

If you prefer to run the notebooks on your device, create a virtual environment using the requirements.txt file:
```
conda create -n xai python=3.11
conda activate xai
pip install -r requirements_xai-for-random-forest.txt
```

Once your environment is created, clone `2026-DKFZ` brach branch of the repo using the following command:

```
git clone --branch 2026-DKFZ https://github.com/HelmholtzAI-Consultants-Munich/XAI-Tutorials.git
```

## Code of Conduct

Participants are expected to follow our code of conduct. In order to have a nice and collaborative environment, please follow these rules:

- Treat others with respect and professionalism.
- Avoid side conversations while others are speaking.
- Raise your hand if you would like to ask a question or contribute to the discussion.

If you experience any issues or concerns that you would prefer not to address publicly, please speak privately with one of the mentors.

## Contributions

Comments and input are very welcome! If you have a suggestion or think something should be changed, please open an issue, submit a pull request or send an email to [Lisa Barros de Andrade e Sousa](mailto:lisa.barros@helmholtz-munich.de) or [Donatella Cea](mailto:donatella.cea@helmholtz-munich.de).

All content is publicly available under the Creative Commons Attribution License: https://creativecommons.org/licenses/by/4.0/
