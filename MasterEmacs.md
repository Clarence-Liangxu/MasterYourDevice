# Master Emacs
## Disable backup
```elisp
(setq make-backup-files nil)
# or to another directory
(setq backup-directory-alist (quote (("." . "~/.backups"))))
```