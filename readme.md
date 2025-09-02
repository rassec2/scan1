`scan1` 是一个集成的安全扫描工具，它包含了多个功能模块：

**保证如下5种工具已经安装**

* **域名枚举** (subfinder)
* **端口扫描** (naabu)
* **网页爬取** (katana)
* **漏洞扫描** (nuclei)
* **HTTP探测** (httpx)

---

### 用法 (Usage)

`scan1 [command]`

---

### 可用命令 (Available Commands)

| 命令 | 描述 |
| :--- | :--- |
| `completion` | 为指定 shell 生成自动补全脚本 |
| `crawl` | 执行网页爬取 |
| `enum` | 执行域名枚举 |
| `help` | 获取任何命令的帮助信息 |
| `port` | 执行端口扫描 |
| `scan` | 执行完整的扫描流程 |
| `vuln` | 执行漏洞扫描 |

---

### 标志 (Flags)

| 标志 | 描述 |
| :--- | :--- |
| `-f, --config string` | 配置文件路径 |
| `-h, --help` | 获取 `scan1` 的帮助信息 |
| `-o, --output string` | 输出目录 (默认 "results") |
| `-s, --severity string` | 漏洞严重级别筛选 (low,medium,high,critical) (默认 "low,medium,high,critical") |
| `-t, --target string` | 目标域名或 IP |
| `-l, --target-file string` | 包含目标列表的文件路径 |
| `-T, --targets strings` | 多个目标域名或 IP |
| `-c, --threads int` | 并发线程数 (默认 50) |
| `-w, --timeout int` | 超时时间 (秒) (默认 30) |
| `-v, --verbose` | 详细输出 |

---

使用 `scan1 [command] --help` 可以获取关于某个命令的更多信息。
