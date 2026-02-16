# Quick Start Guide / クイックスタートガイド

Get started with the AI & Robotics Events Japan repository in minutes!
AI・ロボティクスイベント Japanリポジトリを数分で始めましょう！

## For Contributors / 貢献者向け

### 1. Clone the Repository / リポジトリをクローン
```bash
git clone https://github.com/AI-Robot-Japan/events.git
cd events
```

### 2. Understand the Structure / 構造を理解
```
events/
├── .clinerules              # AI coding guidelines
├── src/                     # Your code goes here
├── tests/                   # Your tests go here
├── examples/                # Example files
└── docs/                    # Documentation
```

### 3. Start Contributing / 貢献を開始
```bash
# Create a new branch
git checkout -b feature/your-feature

# Make your changes
# ... edit files ...

# Test your changes
# ... run tests ...

# Commit and push
git add .
git commit -m "Add: Your feature description"
git push origin feature/your-feature

# Create a Pull Request on GitHub
```

## For Claude Code Users / Claude Code ユーザー向け

### 1. Open in Your Editor / エディタで開く
Open the repository in your editor with Claude Code enabled.
Claude Codeが有効になっているエディタでリポジトリを開きます。

### 2. Claude Code Will Automatically / Claude Codeは自動的に
- Detect the `.clinerules` file / `.clinerules`ファイルを検出
- Apply coding guidelines / コーディングガイドラインを適用
- Provide context-aware suggestions / コンテキスト認識の提案を提供
- Follow bilingual conventions / バイリンガル規約に従う

### 3. Use Claude Code For / Claude Codeを使用して
- **Generate code**: Ask Claude to create functions, classes, etc.
- **Explain code**: Get explanations of existing code
- **Debug issues**: Get help finding and fixing bugs
- **Write tests**: Generate test cases
- **Document code**: Create documentation

**コード生成**: Claude に関数、クラスなどの作成を依頼
**コード説明**: 既存のコードの説明を取得
**問題のデバッグ**: バグの発見と修正のヘルプを取得
**テスト作成**: テストケースを生成
**コードのドキュメント化**: ドキュメントを作成

## Common Tasks / 一般的なタスク

### Adding an Event / イベントの追加
```bash
# Copy the example template
cp examples/event-example.json data/events/my-event.json

# Edit with your event details
# ... edit my-event.json ...

# Validate JSON
python3 -m json.tool data/events/my-event.json

# Commit
git add data/events/my-event.json
git commit -m "Add: My Event"
```

### Running Tests / テストの実行
```bash
# When tests are implemented
npm test  # or the appropriate test command
```

### Building Documentation / ドキュメントのビルド
```bash
# Add your documentation to docs/
# Follow the bilingual format in existing docs
```

## Need Help? / ヘルプが必要？

1. **Check Documentation** / ドキュメントを確認
   - [Full Documentation](docs/README.md)
   - [Claude Code Setup](docs/claude-code-setup.md)
   - [Contributing Guide](CONTRIBUTING.md)

2. **Open an Issue** / issueを開く
   - [Bug Report](.github/ISSUE_TEMPLATE/bug_report.yml)
   - [Feature Request](.github/ISSUE_TEMPLATE/feature_request.yml)

3. **Ask the Community** / コミュニティに質問
   - Create a discussion on GitHub
   - GitHubでディスカッションを作成

## Best Practices / ベストプラクティス

✅ **DO / すること**
- Follow the `.clinerules` guidelines / `.clinerules`ガイドラインに従う
- Write tests for new features / 新機能のテストを書く
- Update documentation / ドキュメントを更新
- Use descriptive commit messages / 説明的なコミットメッセージを使用
- Keep PRs focused and small / PRは集中的で小規模に保つ

❌ **DON'T / しないこと**
- Commit sensitive data / 機密データをコミット
- Break existing tests / 既存のテストを壊す
- Skip documentation / ドキュメントをスキップ
- Make unrelated changes / 無関係な変更を行う

## Quick Commands Reference / クイックコマンドリファレンス

```bash
# Git basics / Git基本
git status                          # Check status
git add .                          # Stage all changes
git commit -m "message"            # Commit changes
git push                           # Push to remote

# Validation / 検証
python3 -m json.tool file.json     # Validate JSON
grep -r '[[:blank:]]$' .           # Check trailing whitespace

# Project structure / プロジェクト構造
tree -L 2                          # View directory tree
ls -la                             # List all files
```

## Ready to Start! / 始める準備完了！

🚀 You're all set! Start coding with Claude Code assistance.
準備完了！Claude Codeの支援でコーディングを始めましょう。

📖 For detailed information, see the [full documentation](docs/README.md).
詳細情報については、[完全なドキュメント](docs/README.md)を参照してください。

🤝 Welcome to the AI & Robotics Events Japan community!
AI・ロボティクスイベント Japanコミュニティへようこそ！
