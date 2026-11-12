<div align="center">

<table width="100%">
<tr>
<td width="64%" valign="middle">
<h1>sunan</h1>
<h2>systems and security engineer</h2>
<p>build. break. fix. repeat.</p>
<p>final-year B.E. ISE at RNSIT, Bengaluru. linux internals, automotive security, secure firmware.</p>
<p><a href="https://sunanditha-archive.netlify.app">portfolio</a> · <a href="https://linkedin.com/in/sunanditha-b-s">linkedin</a></p>
</td>
<td width="36%" valign="middle" align="center">
<img src="https://avatars.githubusercontent.com/u/202910194?u=a5f8c52db31f9ff5be12479ba86c2fb7e691bdf6&amp;v=4" width="180" alt="sunan GitHub avatar" />
</td>
</tr>
</table>

</div>

## what i work on

<table width="100%">
<tr>
<td width="33%" valign="top"><h3>linux and kernel</h3><p>pcie drivers, kernel debugging with gdb and ftrace, initramfs and grub recovery, arch linux daily driver.</p></td>
<td width="33%" valign="top"><h3>automotive security</h3><p>can bus intrusion detection, uds (iso 14229), socketcan, and a published threat model for adaptive can ids.</p></td>
<td width="33%" valign="top"><h3>firmware and ota</h3><p>signed firmware updates, x.509 trust chains, a/b partitions, red-teamed against rollback and mitm.</p></td>
</tr>
</table>

## selected work

| project | what it is | stack |
| --- | --- | --- |
| [**pciedriv**](https://github.com/sunandithabs/pciedriv) | linux pcie driver for qemu's edu device. bar/mmio, msi, coherent dma, ioctl interface, debugfs stats, and a qemu test harness with 11 checks including 4-process concurrency. | C, linux kernel, qemu, gdb |
| [**canary**](https://github.com/sunandithabs/canary) | real-time can bus ids on live socketcan. 6 detectors for spoofing, replay, flooding, and malformed frames, with the 15-bit crc in C bridged via ctypes. 47 tests. | Python, C, pytest |
| [**bolt**](https://github.com/sunandithabs/bolt) | secure boot and ota toolkit. signed firmware, 2-tier x.509 chain, a/b partitions, red-teamed against rollback, signature stripping, mitm, and power loss. 33 tests. | Python, RSA-PSS, x.509 |
| [**excalibur**](https://doi.org/10.13140/RG.2.2.29872.52489) | lifecycle threat model for adaptive can ids. timestamp-drift attack validated on real ORNL ROAD traffic, plus a median/MAD filter that suppresses it. submitted to C2IS 2026. | Python |
| [**simulyn**](https://github.com/sunandithabs/simulyn) | containerized virtual lab platform. sandboxed multi-language code execution, jwt-verified exam proctoring, 247 tests, piloted with 8 students. csitss 2026 paper. | TypeScript, NestJS, Docker |

## toolkit

**languages:** C, Python, Bash, TypeScript, SQL

**systems:** linux (arch), kernel modules, pcie, mmio, dma, msi, qemu, gdb, ftrace

**security:** secure boot, authenticated ota, x.509, rsa-pss, can security, uds, mitre att&ck, osint

**practice:** pytest, docker compose, git, bug bounty (intigriti, hackerone), threat intel profiles

## recognition

- 1st place, national: TechVision '26 project expo (CMRIT)
- 1st place, national: "escape and exploit" cybersecurity competition
- top 15, national: zeroday arena ctf
- paper at CSITSS 2026: simulyn, virtual engineering labs

<hr />

<table width="100%">
<tr>
<td width="62%" valign="middle"><h2>open to systems, security, and embedded work</h2><p>internships in automotive cybersecurity, embedded linux, and low-level engineering.</p></td>
<td width="38%" valign="middle" align="right"><a href="https://linkedin.com/in/sunanditha-b-s">linkedin</a></td>
</tr>
</table>
