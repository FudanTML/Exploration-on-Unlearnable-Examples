# Exploration-on-Unlearnable-Examples

### Problem Statement
The volume of ``free" data on the internet has been key to the current success of deep learning. A recent report shows a private company maintaining an extremely large-scale facial image database for training commercial models, and the database is even larger than the one used by government agencies [1]. The data is collected from social media without the user's consent or acknowledgment. This raises privacy concerns about the unauthorized exploitation of personal data for training commercial models. To prevent personal data from being freely exploited by others, Unlearnable Examples [2] have been proposed. It demonstrated effectively can prevent the model from learning useful patterns by introducing error-minimization noise. However, there are still a few challenges regarding practical use has yet to be solved. 

### Project Goals  
- **Practical use of unlearnable examples against representational learning:** Unlearnable examples are only effective against representational learning if the entire dataset is unlearnable. This is not practical in real-world settings. Considering a user post unlearnable examples online, is it possible to create a corresponding noise that can help the user evade recognition by the camera at test time? A user could ware specially made glass or a t-shirt, e.g., a combination of unlearnable examples and physical adversarial attacks. In this project, we encourage you to develop an effective method that can produce a pair of unlearnable examples with physical adversarial objects. 

- **Unlearnable examples in other domains and their understanding:** Unlearnable example has only been investigated in image space in existing works. It has been found the noise used to create them is a form of linear separable features [3]. It is unclear how to create unlearnable examples in other domains, such as text, audio, or video. If they exist, are there any interesting understanding or intriguing properties?  In this project, we encourage you to explore unlearnable examples of other types of data and gain additional insights about the unlearnable examples. 

`Note：` Consider the challenge of the task above. You can choose one of the topics or other closely related topics in which you are interested.

`Code:` You may follow the following as an example
  - [Unlearnable Examples](https://github.com/HanxunH/Unlearnable-Examples)

[1] Kashmir Hill. The secretive company that might end privacy as we know it. In Ethics of Data and Analytics. 2020.\
[2] Huang, H., Ma, X., Erfani, S. M., Bailey, J., & Wang, Y. Unlearnable Examples: Making Personal Data Unexploitable. ICLR 2021.\
[3] Yu, D., Zhang, H., Chen, W., Yin, J., & Liu, T. Y. Availability attacks create shortcuts. SIGKDD 2022.
