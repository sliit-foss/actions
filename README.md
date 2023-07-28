<br/>

<p align="center">
  <img src="https://github.com/sliit-foss/actions/assets/73662613/0a07640a-0559-406e-a23d-0dfe0be0a91a" width="158" height="158" alt="Timekeeper Logo"/>  
</p>

<div id="user-content-toc" align="center">
  <ul>
    <summary><h1 style="display: inline-block;">Actions</h1></summary>
  </ul>
</div>

<p align="center">
  <a aria-label="SLIIT FOSS logo" href="https://sliitfoss.org">
    <img src="https://img.shields.io/badge/Made_by_the_SLIIT_FOSS_Community-blue">
  </a>
  <a aria-label="License" href="https://github.com/sliit-foss/actions/blob/main/LICENSE">
    <img alt="" src="https://img.shields.io/badge/License-MIT-yellow.svg">
  </a>
</p>

<br/>

A collection of reusable Github Actions for both internal and external use

## Example Usage

```yaml
- name: Upload build files 📤
  uses: sliit-foss/actions/preview-deployments/postbuild@main
```

## Commit messages

- We follow conventional commits during our development workflow as a good practice. More information can be found at their official [documentation](https://www.conventionalcommits.org/en/v1.0.0-beta.4/#examples)
- Refer the [commitlint.config.js](https://github.com/sliit-foss/actions/blob/main/commitlint.config.cjs) file for a full list of supported commit message prefixes
