# *sd-all-prompt-wildcard*
This is an updated version of wildcards that allow the user to use wildcards in both the positive & **negative** prompts.

![Wildcard-Example]()

Allows you to use `__wildcard-name__` syntax in your pos &/or **neg** prompts to get a random line from a file named `wildcard-name.txt` in the wildcards directory &/or from here [sd-dynamic-prompts](https://github.com/adieyal/sd-dynamic-prompts).

## News
- **2024-08-02:** [Release of sd-all-prompt-wildcards](https://github.com/MackinationsAi/sd-all-prompt-wildcards).
- **2024-08-03:** Awaiting approval for this extension to be added to the [stable-diffusion-webui-extensions index](https://github.com/AUTOMATIC1111/stable-diffusion-webui-extensions).

## Install from webui Extensions Tab
Once approved, users will be able to intall by going to the `Extensions Tab` & install directly from the index. Or manually from the `Extensions Tab -> Install from URL`, paste-in `https://github.com/MackinationsAi/sd-all-prompt-wildcards` into URL field, & press Install. *(This extension works for both a1111 & forge)

## Install Manually
From your base `stable-diffusion-webui/extensions` or `stable-diffusion-webui-forge/extensions` directory by running the following command:

```
git clone https://github.com/MackinationsAi/sd-all-prompt-wildcards.git
```
Then restart your webui.

## Recognition
The original underlying code from extension script https://github.com/AUTOMATIC1111/stable-diffusion-webui-wildcards
