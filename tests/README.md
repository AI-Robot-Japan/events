# Tests / テスト

This directory contains test files for the project.
このディレクトリには、プロジェクトのテストファイルが含まれています。

## Structure / 構造

```
tests/
├── README.md          # This file / このファイル
├── unit/              # Unit tests / ユニットテスト
├── integration/       # Integration tests / 統合テスト
└── fixtures/          # Test fixtures and data / テストフィクスチャとデータ
```

## Running Tests / テストの実行

Instructions for running tests will be added as the test suite is developed.
テストスイートの開発に伴い、テスト実行の手順が追加されます。

Example commands:
コマンドの例：

```bash
# Run all tests / すべてのテストを実行
npm test

# Run specific test file / 特定のテストファイルを実行
npm test -- path/to/test.js

# Run with coverage / カバレッジ付きで実行
npm test -- --coverage
```

## Test Guidelines / テストガイドライン

When writing tests:
テストを書く際：

1. **Test naming** / テストの命名
   - Use descriptive names that explain what is being tested
   - テスト内容を説明する分かりやすい名前を使用

2. **Test organization** / テストの整理
   - Group related tests together
   - 関連するテストをまとめる

3. **Test coverage** / テストカバレッジ
   - Aim for high test coverage
   - 高いテストカバレッジを目指す
   - Focus on critical paths first
   - まず重要なパスに焦点を当てる

4. **Test independence** / テストの独立性
   - Each test should be independent
   - 各テストは独立している必要がある
   - Tests should not depend on the order of execution
   - テストは実行順序に依存しない

## Test Structure / テスト構造

Typical test structure:
典型的なテスト構造：

```javascript
describe('Feature or Component Name', () => {
  // Setup
  beforeEach(() => {
    // Initialize test data
  });

  // Teardown
  afterEach(() => {
    // Clean up
  });

  it('should do something specific', () => {
    // Arrange
    const input = ...;
    
    // Act
    const result = functionUnderTest(input);
    
    // Assert
    expect(result).toBe(expected);
  });
});
```

## Best Practices / ベストプラクティス

- Write tests before or alongside code (TDD) / コードの前または並行してテストを書く（TDD）
- Keep tests simple and readable / テストはシンプルで読みやすく保つ
- Test edge cases and error conditions / エッジケースとエラー条件をテスト
- Mock external dependencies / 外部依存関係をモック化
- Update tests when code changes / コード変更時にテストを更新
