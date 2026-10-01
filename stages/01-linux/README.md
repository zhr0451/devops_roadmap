# Этап 1. Linux

## Фокус по итогам входного теста (Issue #3)

Темы, в которых есть пробелы. На них тратим больше времени:

- [ ] Права доступа: `rwx`, восьмеричная запись, `chmod`, `chown`, `umask`, SUID/SGID/sticky bit
- [ ] Процессы и потоки: чем отличаются, PID, PPID, `ps`, `top`, `/proc`
- [ ] PID 1 и init: роль systemd, юниты, `systemctl`
- [ ] Диагностика сервисов: `systemctl status`, `journalctl -u`, почему сервис не стартует
- [ ] Жёсткие и символические ссылки, inode
- [ ] Сигналы: SIGHUP, SIGTERM, SIGKILL; `kill`, `nohup`, `setsid`, tmux
- [ ] Иерархия файловой системы (FHS): `/etc`, `/var`, `/var/log`
- [ ] Логи: systemd-journald, `/var/log`, `journalctl`

Файлы этапа: `theory.md`, `questions.md`, `tasks/`, `retro.md`.
