# 1. Create submission zip file

## Single student:

```bash
bash create_submission.sh --id <ID> --source <SOURCE_DIR>
```

Notes:
- replace `<ID>` with the student ID submitting the exercise
- replace `<SOURCE_DIR>` with the directory of your `/ex3` source code

## or Team:

```bash
bash create_submission.sh --team <ID1>,<ID2>,... --source <SOURCE_DIR>
```

Note:
- replace `<ID1>`, `<ID2>`, ... with the student IDs in the team

# 2. Run all tests

```bash
bash run_all_tests.sh <ID>.zip
```

Note:
- replace `<ID>` with the student ID submitting the exercise

---

Disclaimers:
- May or may not include bugs!
- Send PRs for fixes/improvements!


