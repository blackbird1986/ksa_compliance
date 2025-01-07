KSA Compliance
--------------

A free and open-source Frappe application for KSA Compliance (ZATCA Integration), offering support for both Phase 1 and Phase 2.

### Main Features

1.  ZATCA Phase 1 - compliance
2.  ZATCA Phase 2 - compliance
3.  Simplified invoice
4.  Standard Invoice
5.  Wizard onboarding
6.  Automatic ZATCA CLI setup
7.  Tax exemption reasons
8.  ZATCA dashboard
9.  Embedded Invoice QR without impacting storage
10. Embedded Invoice XML without impacting storage
11. ZATCA phase 1 print format
12. ZATCA phase 2 print format
13. Resend process
14. Rejection process
15. ZATCA Integration Live and Batch modes
16. Multi-company support
17. Multi-device setup
18. Embedded compliance checks log
19. System XML validation
20. Support ZATCA Sandbox

### How to Install

-   **Self Hosting:**

```
bench get-app git@github.com:lavaloon-eg/ksa_compliance.git --branch master
```

```
bench setup requirements
```

```
bench build --app ksa_compliance
```

```
bench restart
```

```
bench  --site [your.site.name] install-app ksa_compliance
```

```
bench  --site [your.site.name] migrate
```