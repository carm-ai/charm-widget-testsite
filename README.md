**Charm-widget-testsite** is a [Github Pages](https://pages.github.com/) page created to test the embedding of the widgets. 

The Abrigo widgets can be accessed on this url: https://carm-ai.github.io/charm-widget-testsite/abrigo_test.html

To update any widget parameter, follow these steps: 

1. On the main repository [page](https://github.com/carm-ai/charm-widget-testsite), press `.`. This will open the porject in Github's [web-based editor](https://docs.github.com/en/codespaces/the-githubdev-web-based-editor). Another way to access the web-editor directly is with this link: https://github.dev/carm-ai/charm-widget-testsite
2. From the left-hand menu, under **Explorer**, open the **abrigo_test.html** file.
3. The page has added a lot ow widget elements, but many of them are commented out. Remove the comments if you need to test more widgets.
4. Update the `<charm-score>` or `<charm-entity-monitor>` widget parameters by simply copy-paste the correct values. Save the changes with `ctrl` + `s`.
5. When you save the changes, on the left-hand menu look for the **Source control** icon, it should contain a notification for 1 pending change. Open it, click on the abrigo_test.html file to review the changes and if it looks ok, press the `+` sign. This will `Stage changes` and make the file ready to commit.
6. At the top input field enter commit message (not really relevant for this repository, it can be simple `update` text)
7. Click the **Commit & push** button. 
8. The deployment will start automatically after this, it runs for about a minute. The deployment progress can be tracked on the [deployments](https://github.com/carm-ai/charm-widget-testsite/deployments) page.
