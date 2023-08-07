# A very opinionated Collection of Linter Rules for Flutter and Dart (based on `flutter_lints` and `lints`)

## Getting started

Add this package as a `devDependency`.

```sh
flutter pub add --dev extended_dart_lints
```

or

```sh
dart pub add --dev extended_dart_lints
```

Alternatively, you can directly add it to the `devDependencies` section in your `pubspec.yaml`:

```yaml
dev_dependencies:
  extended_dart_lints: ^0.0.1
```

> Note: While this package is unpublished, use:

```yaml
dev_dependencies:
  extended_dart_lints:
    git:
      url: git@github.com:bjoernahrens/extended_dart_lints.git
      ref: main
```

## Usage

Add the following line to your `analysis_options.yaml`:

```yaml
include: package:extended_dart_lints/lints.yaml
```

Following that, you can still easily enable or disable rules as you please.

```yaml
linter:
  rules:
    prefer_single_quotes: false
```

## Additional information

Checkout the packages [`flutter_lints`](https://pub.dev/packages/flutter_lints) and [`lints`](https://pub.dev/packages/lints).

## Applied Rules

### Group _Errors_

- [`avoid_dynamic_calls`](https://dart.dev/tools/linter-rules/avoid_dynamic_calls)
- [`avoid_slow_async_io`](https://dart.dev/tools/linter-rules/avoid_slow_async_io)
- [`cancel_subscriptions`](https://dart.dev/tools/linter-rules/cancel_subscriptions)
- [`close_sinks`](https://dart.dev/tools/linter-rules/close_sinks)
- [`collection_methods_unrelated_type`](https://dart.dev/tools/linter-rules/collection_methods_unrelated_type)
- [`comment_references`](https://dart.dev/tools/linter-rules/comment_references)
- [`diagnostic_describe_all_properties`](https://dart.dev/tools/linter-rules/diagnostic_describe_all_properties)
- [`discarded_futures`](https://dart.dev/tools/linter-rules/discarded_futures)
- [`no_adjacent_strings_in_list`](https://dart.dev/tools/linter-rules/no_adjacent_strings_in_list)
- [`prefer_relative_imports`](https://dart.dev/tools/linter-rules/prefer_relative_imports)
- [`throw_in_finally`](https://dart.dev/tools/linter-rules/throw_in_finally)
- [`unnecessary_statements`](https://dart.dev/tools/linter-rules/unnecessary_statements)

### Group _Style_

- [`always_declare_return_types`](https://dart.dev/tools/linter-rules/always_declare_return_types)
- [`avoid_catches_without_on_clauses`](https://dart.dev/tools/linter-rules/avoid_catches_without_on_clauses)
- [`avoid_catching_errors`](https://dart.dev/tools/linter-rules/avoid_catching_errors)
- [`avoid_classes_with_only_static_members`](https://dart.dev/tools/linter-rules/avoid_classes_with_only_static_members)
- [`avoid_double_and_int_checks`](https://dart.dev/tools/linter-rules/avoid_classes_with_only_static_members)
- [`avoid_escaping_inner_quotes`](https://dart.dev/tools/linter-rules/avoid_escaping_inner_quotes)
- [`avoid_final_parameters`](https://dart.dev/tools/linter-rules/avoid_final_parameters)
- [`avoid_implementing_value_types`](https://dart.dev/tools/linter-rules/avoid_implementing_value_types)
- [`avoid_js_rounded_ints`](https://dart.dev/tools/linter-rules/avoid_js_rounded_ints)
- [`avoid_multiple_declarations_per_line`](https://dart.dev/tools/linter-rules/avoid_multiple_declarations_per_line)
- [`avoid_positional_boolean_parameters`](https://dart.dev/tools/linter-rules/avoid_positional_boolean_parameters)
- [`avoid_private_typedef_functions`](https://dart.dev/tools/linter-rules/avoid_private_typedef_functions)
- [`avoid_redundant_argument_values`](https://dart.dev/tools/linter-rules/avoid_redundant_argument_values)
- [`avoid_returning_this`](https://dart.dev/tools/linter-rules/avoid_returning_this)
- [`avoid_setters_without_getters`](https://dart.dev/tools/linter-rules/avoid_setters_without_getters)
- [`avoid_types_on_closure_parameters`](https://dart.dev/tools/linter-rules/avoid_types_on_closure_parameters)
- [`avoid_unused_constructor_parameters`](https://dart.dev/tools/linter-rules/avoid_unused_constructor_parameters)
- [`avoid_void_async`](https://dart.dev/tools/linter-rules/avoid_void_async)
- [`cascade_invocations`](https://dart.dev/tools/linter-rules/cascade_invocations)
- [`dangling_library_doc_comments`](https://dart.dev/tools/linter-rules/dangling_library_doc_comments)
- [`deprecated_consistency`](https://dart.dev/tools/linter-rules/deprecated_consistency)
- [`join_return_with_assignment`](https://dart.dev/tools/linter-rules/join_return_with_assignment)
- [`leading_newlines_in_multiline_strings`](https://dart.dev/tools/linter-rules/leading_newlines_in_multiline_strings)
- [`lines_longer_than_80_chars`](https://dart.dev/tools/linter-rules/lines_longer_than_80_chars)
- [`missing_whitespace_between_adjacent_strings`](https://dart.dev/tools/linter-rules/missing_whitespace_between_adjacent_strings)
- [`noop_primitive_operations`](https://dart.dev/tools/linter-rules/noop_primitive_operations)
- [`one_member_abstracts`](https://dart.dev/tools/linter-rules/one_member_abstracts)
- [`only_throw_errors`](https://dart.dev/tools/linter-rules/only_throw_errors)
- [`parameter_assignments`](https://dart.dev/tools/linter-rules/parameter_assignments)
- [`prefer_asserts_in_initializer_lists`](https://dart.dev/tools/linter-rules/prefer_asserts_in_initializer_lists)
- [`prefer_asserts_with_message`](https://dart.dev/tools/linter-rules/prefer_asserts_with_message)
- [`prefer_constructors_over_static_methods`](https://dart.dev/tools/linter-rules/prefer_constructors_over_static_methods)
- [`prefer_final_in_for_each`](https://dart.dev/tools/linter-rules/prefer_final_in_for_each)
- [`prefer_final_locals`](https://dart.dev/tools/linter-rules/prefer_final_locals)
- [`prefer_if_elements_to_conditional_expressions`](https://dart.dev/tools/linter-rules/prefer_if_elements_to_conditional_expressions)
- [`prefer_int_literals`](https://dart.dev/tools/linter-rules/prefer_int_literals)
- [`prefer_null_aware_method_calls`](https://dart.dev/tools/linter-rules/prefer_null_aware_method_calls)
- [`prefer_single_quotes`](https://dart.dev/tools/linter-rules/prefer_single_quotes)
- [`sort_pub_dependencies`](https://dart.dev/tools/linter-rules/sort_pub_dependencies)
- [`sort_unnamed_constructors_first`](https://dart.dev/tools/linter-rules/sort_unnamed_constructors_first)
- [`unawaited_futures`](https://dart.dev/tools/linter-rules/unawaited_futures)
- [`unnecessary_await_in_return`](https://dart.dev/tools/linter-rules/unnecessary_await_in_return)
- [`unnecessary_lambdas`](https://dart.dev/tools/linter-rules/unnecessary_lambdas)
- [`unnecessary_library_directive`](https://dart.dev/tools/linter-rules/unnecessary_library_directive)
- [`unnecessary_null_aware_operator_on_extension_on_nullable`](https://dart.dev/tools/linter-rules/unnecessary_null_aware_operator_on_extension_on_nullable)
- [`unnecessary_null_checks`](https://dart.dev/tools/linter-rules/unnecessary_null_checks)
- [`unnecessary_parenthesis`](https://dart.dev/tools/linter-rules/unnecessary_parenthesis)
- [`unnecessary_raw_strings`](https://dart.dev/tools/linter-rules/unnecessary_raw_strings)
- [`unnecessary_to_list_in_spreads`](https://dart.dev/tools/linter-rules/unnecessary_to_list_in_spreads)
- [`use_colored_box`](https://dart.dev/tools/linter-rules/use_colored_box)
- [`use_decorated_box`](https://dart.dev/tools/linter-rules/use_decorated_box)
- [`use_enums`](https://dart.dev/tools/linter-rules/use_enums)
- [`use_if_null_to_convert_nulls_to_bools`](https://dart.dev/tools/linter-rules/use_if_null_to_convert_nulls_to_bools)
- [`use_is_even_rather_than_modulo`](https://dart.dev/tools/linter-rules/use_is_even_rather_than_modulo)
- [`use_late_for_private_fields_and_variables`](https://dart.dev/tools/linter-rules/use_late_for_private_fields_and_variables)
- [`use_named_constants`](https://dart.dev/tools/linter-rules/use_named_constants)
- [`use_raw_strings`](https://dart.dev/tools/linter-rules/use_raw_strings)
- [`use_setters_to_change_properties`](https://dart.dev/tools/linter-rules/use_setters_to_change_properties)
- [`use_string_buffers`](https://dart.dev/tools/linter-rules/use_string_buffers)
- [`use_super_parameters`](https://dart.dev/tools/linter-rules/use_super_parameters)
- [`use_test_throws_matchers`](https://dart.dev/tools/linter-rules/use_test_throws_matchers)

## Development

This project is configured with `husky` and `lint-staged` to automatically format code pre-commit.
To install the pre-commit hook, you need to install and run `husky` via `npm`/`npx`.
