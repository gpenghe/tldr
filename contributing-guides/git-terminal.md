Most people submit pull requests to the tldr project
[using GitHub's web interface][pr-howto].

If you prefer, you can do most of the process using the command line instead.
The overall process should look somewhat like this:

1. Fork the tldr repository on the github web interface.

2. Clone your fork locally:  
  `git clone https://github.com/{{your_username}}/tldr.git && cd tldr`

3. Make your changes (edit existing files or create new ones)

4. Commit the changes (following the [commit message guidelines][commit-msg]):  
  `git commit --all -m "{{commit_message}}"`

5. Push the commit(s) to your fork:  
  `git push origin`

6. Go to the github page for your fork and click the green "pull request" button.

Please only send related changes in the same pull request.
Typically a pull request will include changes in a single file.
(Exceptions are [occasionally acceptable][mass-changes].)

[pr-howto]: ../CONTRIBUTING.md#submitting-a-pull-request
[commit-msg]: ../CONTRIBUTING.md#commit-message
[mass-changes]: https://github.com/tldr-pages/tldr/pulls?&q=is:pr+is:merged+label:"mass+changes"
