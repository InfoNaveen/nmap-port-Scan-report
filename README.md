# nmap-port-Scan-report

# Network Port Scan Report

## Objective
[span_0](start_span)The objective of this task was to use Nmap to discover open ports on devices within the local network to better understand the network's exposure[span_0](end_span).

## Tool Used
* *[span_1](start_span)Tool:* Nmap (Network Mapper)[span_1](end_span)

## Process
[span_2](start_span)A TCP SYN scan was performed on the local network to identify active hosts and open ports[span_2](end_span).

* *Network Range Identified:* 10.154.253.0/24
* *Command Executed:* nmap -sS 10.154.253.0/24 > nmap_scan_results.txt

## Scan Results
[span_3](start_span)[span_4](start_span)The complete output of the scan, which includes the IP addresses of discovered devices and their open ports, was saved to the nmap_scan_results.txt file and is included in this repository[span_3](end_span)[span_4](end_span).

These open ports represent services running on the network devices. [span_5](start_span)Each open port is a potential entry point, and identifying them is the first step in assessing potential security risks[span_5](end_span). [span_6](start_span)This task provides a foundational understanding of network reconnaissance skills[span_6](end_span).
