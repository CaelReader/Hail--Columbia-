outcome = {
    header = je_standard_completion_header
    effect_header = je_standard_on_completion_header
    color = "gold_positive"
    conclusion_desc = je_standard_completion_conclusion_desc
    trigger = {

    }
    effect = {

    }
}

outcome = {
    header = je_standard_failure_header
    effect_header = je_standard_on_failure_header
    color = "blue_negative"
    conclusion_desc = je_standard_failure_conclusion_desc
    trigger = {

    }
    effect = {

    }
}

outcome = {
    flags = { hidden invalid_outcome }
    conclusion_desc = je_standard_failure_conclusion_desc
    trigger = {

    }
}

outcome = {
    header = JOURNAL_ENTRY_TIMEOUT
    effect_header = JOURNAL_ENTRY_ON_TIMEOUT
    flags = { timeout }
    conclusion_desc = JOURNAL_ENTRY_TIMEOUT_CONCLUSION_DESC
    effect = {

    }
}

        event_outcome_effect_desc = {
            header = usfp_manifest_destiny.19.a
            effect = {
                execute_event_option = {
                    event = usfp_manifest_destiny.19
                    option = 0
                }
            }
        }

flags = { historical }

    dlc = dlc_usfp
    activation_description = { always = yes }