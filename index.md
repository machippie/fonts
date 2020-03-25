
## Default Variables

### fonts_casks

List of casks to install

#### Default value

```yaml
fonts_casks:
  - font-anonymice-powerline
  - font-inconsolata-dz-for-powerline
  - font-menlo-for-powerline
  - font-roboto-mono-for-powerline
  - font-consolas-for-powerline
  - font-inconsolata-for-powerline
  - font-meslo-for-powerline
  - font-source-code-pro-for-powerline
  - font-dejavu-sans-mono-for-powerline
  - font-inconsolata-for-powerline-bold
  - font-monofur-for-powerline
  - font-ubuntu-mono-derivative-powerline
  - font-droid-sans-mono-for-powerline
  - font-inconsolata-g-for-powerline
  - font-noto-mono-for-powerline
  - font-fira-mono-for-powerline
  - font-liberation-mono-for-powerline
  - font-powerline-symbols
  - font-fira-code
```

### fonts_taps

List of taps to install

#### Default value

```yaml
fonts_taps:
  - homebrew/cask-fonts
```

### fonts_user

User to run user-specific commands

#### Default value

```yaml
fonts_user | default(homebrew_user) | default(ansible_user_id)
```
## Dependencies

None

## License

Apache-2.0

## Author

Thomas Boerger
