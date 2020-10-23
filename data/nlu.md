## intent:greet
- hey
- hello
- hi
- good morning
- good evening
- hey there

## intent:name_or_miscellaneous

nlu:
- lookup: name
  examples:
    - [Jason](name)
    - [James](name)
    - [Tommy](name)
    - [Houston](name)

- lookup: action
  examples:
    - [Add](action)
    - [Open](action)
    - [Show](action)
    - [Delete](action)
    - [Edit](action)
    - [print](action)

- lookup: subject
  examples:
    - [patient](subject)

## intent:open_patient_chart
- open [patient](subject) [chart](patient's_what?)
- [patient](subject) chart
- [chart](patient's_what?)

## intent:add_patient_note
- [add](action) patient [note](patient's_what?)
- add note
- [note](patient's_what?)

## intent:open_patient_xray
- open [patient](subject) [xray](patient's_what?)
- open [patient](subject) [x-ray](patient's_what?)
- open [xray](patient's_what?)
- open [xray](patient's_what?)

## intent:add_note_to_patient_lab_results
- add patient [note](patient's_what?) [to lab results](to_patient's_what?)
- add note [to lab results](to_patient's_what?)
- edit [patient's](subject) [lab results](to_patient's_what?)

## intent:add_patient
- add patient(subject)
- [new](adjective) patient(subject)
- [new](adjective)

## intent:show_patient_report
- show [report](patient's_what?)
- [report](patient's_what?)

## intent:print_patient_report
- [print](action) [report](patient's_what?)
- print patient's report
- print

