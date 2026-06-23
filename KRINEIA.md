# KRINEIA.md — adversary-emulation-playbook

krineia_manifest_version: "0.1"
schema: "krineia-manifest@0.1"

repo:
  full_name: "hummbl-dev/adversary-emulation-playbook"
  default_branch: "master"
  visibility: "public"

authority:
  steward: "HUMMBL Research Institute"
  approving_human: "Reuben Bowlby"
  source_of_record: "git"
  receipt_authority: "external_observer"

governance_profile:
  status: "adopted"
  krineia_required: true
  trust_root_mode: "deployment_asserted"

chains:
  primary:
    chain_id: "adversary-emulation-playbook-primary"
    storage: "_receipts/krineia/primary.jsonl"
    genesis_policy: "repo_bootstrap"
    hash_algorithm: "sha256"

operators:
  allowed: ["append", "project", "cut"]
  forbidden: ["update", "delete", "rewrite", "summarize_and_replace", "score_and_train"]

last_reviewed: "2026-06-23"
---

Archived repo — backfilled per §5.5 exemption lift.
