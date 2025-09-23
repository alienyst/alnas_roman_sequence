# Roman Number Sequence

## Extend Sequence to add roman number sequence.

## Installation

To install this module:

1. Download the module and place it in Odoo **Custom Addons** folder.
2. Restart Odoo Server.
3. Go to Odoo UI and Enable **Debug Mode** then open the **Apps** menu.
4. Refresh the list by clicking **Update Apps List**. Finally, you will see `'Roman Number Sequence'` module and click the **Install** button.

## How To Use

1. Go to **Settings** => **Technical** => **Sequence & Identifiers** => **Sequences**.
2. Choose a sequence data, example: `sale.order`.
3. You will see Prefix, Suffix, and Sequence Size tag inputs.
4. If you want to use Roman number as a sequence number, please set 'sequence size' equal to '1' and enable is roman.
5. If you want to use roman number in prefix/suffix, you can add prefix 'roman' in the legend. For example, Day: `%(day)s` => Day in Roman: `%(roman_day)s`, etc.

## Notes

We welcome any feedback and suggestions, especially for improving this module. Thank you!