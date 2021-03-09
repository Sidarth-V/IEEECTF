Name of the challenge: https://zaptech.zapto.org/ctf/forensics-day1/
Category: Forensics


A simple web page with a button saying "you cannot solve me"

On clicking the button we're given an image: https://imgur.com/EEKoc8L

download the image

1. strings
2. cat
3. grep IEEE
4. used stegsolve with filters no luck
5. shubam suggested online tools so https://stylesuxx.github.io/steganography/

output: Vm0weE5GVXhTWGhYV0doWVYwZG9WVmx0Y3pGV1ZteHlWMjVrVjJKSGVIbFdNakZIVmpGS2RHVkVRbFZpUm5CUVZtMTRTMk14VG5OYVJtUk9ZV3RXTTFZeFdtdFRNVTVIVm01T1dHSkdjRmhVVkVwdllqRmFjVkpzV214U2F6VllWbTAxVDFWdFNrZFhiR2hYWWxSV1JGcFdXbHBsVlRGVlZXeGFUbFp1UWxsWFZFSlhZakZrU0ZOcldrOVdlbXhoV1ZSR1lVMHhXWGhYYlVaVFRWWndNRlZ0ZUd0VWJGcHpWMWh3VjFKc2NHaFpWRVpoWXpGd1JtSkdTbWxUUlVwWFZtMTRZVk14WkVkWGJrWlRZbFZhVkZSV1dtRk5SbEp6V2tSU2FGWnJjSHBaYWs1dlZqRktjMWRzVG1GU1JWcEVWbGQ0UTFaVk1VVk5SREE5

seems like base64, so cyberchef

on applying base64 string become shorter base64, applied multiple times(8 times)

Flag: IEEECTF{N0W_Y0U_KN0W_M7_F4V0UR1T3_NUM83R}


