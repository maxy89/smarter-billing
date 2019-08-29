## How to contribute
Everyone is welcome to make suggestions on how this API can be improved by either submitting an issue or a pull-requests.

### Did you find a bug?
- **Ensure the bug was not already reported** by searching on GitHub under [Issues](https://github.com/maxy89/smarter-billing/issues).
- If your unable to find an issue addressing the problem, [open a new one](https://github.com/maxy89/smarter-billing/issues/new). Be sure to include a **title and clear description**, and as much relevant information as possible. Use the xdebug extension for PHP if possible and provide a stack trace with the issue.
- For more detailed information on submitting a bug report and creating an issue, visit our reporting guidelines.
 
### Did you write a patch that fixes a bug?
- Open a new GitHub Pull Request with the patch.
- Ensure the Pull Request description clearly describes the problem and solution. Include the relevant issue number.
- Before submitting your Pull Request, please make sure you have followed the Guidelines below.

### Do you intend to add a new feature or change an existing one?
- Suggest your change or addition by first creating an issue which you can then reference to later.
- Add the appropriate label to the issue: New Feature or Enhancement
- Submit a Pull Request containing the change you wish to make, ensuring you follow the Pull Request Guidelines below.

## Pull Request Guidelines.
- Make sure that your fork is up to date with the 'development' branch first. This helps to prevent conflicts from occuring. A pull request cannot be accepted if there is a conflict.
- Only pull requests from the development branch will be accepted. This ensures that any new code can go through the review process before it reaches the master.
- All commits MUST reference a related issue in the comment. For example, "Part of #xx" or "Fixes #xx". If a related issue does not exist, please first create one.
- Code should follow common practises and the standards as set out in our guidelines. This includes:
  - Indenting of code should consist of 4 spaces, never tabs.
  - Each file should contain an empty line at the end.
  - To make it easier for others to read and understand the code, it is recomended that you space out the code a bit more more. An example is provided below:
    ```php
    if ( exampleFunction( $variable ) ) {
      $exploded = explode( $variable );
    } else {
      $imploded = implode( $variable );
    }
    
    // Note the spacing around brackets.
    // Curly braces should remain on the same line as the 'if' or 'else' statements.
    ```
- Changes that are cosmetic in nature and don't add anything substantial to the stability or functionality of the project will generally not be accepted.
- Acceptance of pull requests is at the descretion of the repository manager. All contributions to this repositiory will be appropriatly credited where possible.

### Repository Structure
This repository has the following branches, each with a specific purpose:
- `master` branch: The master contains all properly reviewed code and is ready for release version.
- `development` branch: This is where all development occurs. All pull requests and commits will go here.

The review process:
- `development`: All development is done in this branch. Nothing will move on until it has been completed here.
- `master`: Once everything has been reviewed and tested appropriately, it will be moved here and considered ready for release.
