# Architecture Decisions

## Why Private Subnets?
To isolate backend systems from direct internet exposure and reduce attack surface.

## Why ALB?
To distribute traffic and provide high availability across instances.

## Why IAM Roles Instead of Access Keys?
To eliminate credential risk and enforce least privilege.

## Biggest Risks
- Misconfigured security groups
- Over-permissive IAM roles

## Improvements for Enterprise Use
- Add centralized logging with SIEM
- Use multi-account architecture
- Add WAF + Shield protection
